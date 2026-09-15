# `brotli-sys` `0.3.2`

Platform: Linux riscv64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned build-level evidence

### Network / source acquisition records

#### Record 1

```json
{
  "acquisition_kind": "git_submodule",
  "argv": [
    "git",
    "submodule",
    "update",
    "--init"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "checkout_root": null,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "acq-ext:git:499ddf9ac3dc8179:e3b0c44298fc1c14",
  "exit_code": 128,
  "kind": "acquisition",
  "output": null,
  "pid": 467215,
  "success": false,
  "tool": "git",
  "url": null,
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 2

```json
{
  "argv": [
    "/usr/bin/git",
    "submodule",
    "update",
    "--init"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/usr/bin/git",
  "pid": 467216,
  "ppid": 467215,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
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
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
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
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-467155-1783994532518387716.map",
  "pid": 467155,
  "ppid": 467111,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-467155-1783994532518387716.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a`

Owner: `brotli-sys` `0.3.2`

### Source files

* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/common/dictionary.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/dec/bit_reader.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/dec/decode.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/dec/huffman.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/dec/state.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/backward_references.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/backward_references_hq.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/bit_cost.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/block_splitter.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/brotli_bit_stream.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/cluster.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/compress_fragment.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/compress_fragment_two_pass.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/dictionary_hash.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/encode.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/entropy_encode.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc/histogram.c`

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
    "-c",
    "brotli/common/dictionary.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467294,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
    "-c",
    "brotli/dec/bit_reader.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467335,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 3

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
    "-c",
    "brotli/dec/decode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467338,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 4

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
    "-c",
    "brotli/dec/huffman.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467355,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 5

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
    "-c",
    "brotli/dec/state.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467360,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 6

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
    "-c",
    "brotli/enc/backward_references.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467366,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 7

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
    "-c",
    "brotli/enc/backward_references_hq.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467391,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 8

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
    "-c",
    "brotli/enc/bit_cost.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467414,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 9

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
    "-c",
    "brotli/enc/block_splitter.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467425,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 10

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
    "-c",
    "brotli/enc/brotli_bit_stream.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467436,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 11

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
    "-c",
    "brotli/enc/cluster.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467448,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 12

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
    "-c",
    "brotli/enc/compress_fragment.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467451,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 13

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "-c",
    "brotli/enc/compress_fragment_two_pass.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467463,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 14

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
    "-c",
    "brotli/enc/dictionary_hash.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467472,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 15

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
    "-c",
    "brotli/enc/encode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467478,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 16

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
    "-c",
    "brotli/enc/entropy_encode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467490,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 17

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o",
    "-c",
    "brotli/enc/histogram.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467494,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/decode.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-decode.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/dec/decode.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467339,
  "ppid": 467338,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
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
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/brotli_bit_stream.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-brotli_bit_stream.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/brotli_bit_stream.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467437,
  "ppid": 467436,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 3

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/entropy_encode.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-entropy_encode.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/entropy_encode.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467491,
  "ppid": 467490,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 4

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/huffman.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-huffman.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/dec/huffman.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467356,
  "ppid": 467355,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 5

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/backward_references.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-backward_references.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/backward_references.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467367,
  "ppid": 467366,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 6

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/compress_fragment_two_pass.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-compress_fragment_two_pass.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/compress_fragment_two_pass.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467464,
  "ppid": 467463,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 7

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/compress_fragment.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-compress_fragment.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/compress_fragment.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467452,
  "ppid": 467451,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 8

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/bit_cost.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-bit_cost.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/bit_cost.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467416,
  "ppid": 467414,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 9

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/state.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-state.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/dec/state.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467362,
  "ppid": 467360,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 10

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/cluster.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-cluster.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/cluster.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467449,
  "ppid": 467448,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 11

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/dictionary_hash.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-dictionary_hash.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/dictionary_hash.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467473,
  "ppid": 467472,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 12

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/common/dictionary.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "e198953d800c79d4-dictionary.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/common/dictionary.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467295,
  "ppid": 467294,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 13

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/block_splitter.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-block_splitter.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/block_splitter.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467426,
  "ppid": 467425,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 14

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/encode.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-encode.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/encode.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467480,
  "ppid": 467478,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 15

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/backward_references_hq.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-backward_references_hq.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/backward_references_hq.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467392,
  "ppid": 467391,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 16

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/bit_reader.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-bit_reader.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/dec/bit_reader.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467336,
  "ppid": 467335,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 17

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/histogram.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-histogram.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/histogram.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467495,
  "ppid": 467494,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
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
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o",
    "..."
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": true,
  "pid": 467525,
  "ppid": 467213,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
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
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "workspace_root": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
      "name": "brotli-sys",
      "version": "0.3.2",
      "manifest_path": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2"
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
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "kind": "exec",
  "pid": 466594,
  "ppid": 466467,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:1190eb007d799be2:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
  "pid": 466594,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:c5eb16742d92300e:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
  "pid": 466594,
  "sha256": "750e5b687b769ef8e1f6a9de3b3b4cc39d771526f669d42b53a924666b856dae",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:135ba558c9da774d:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
  "pid": 466594,
  "sha256": "53140dc43536033138eb06a34e55a6a0ff33641d1e3937f2ad7a716aa3ee683a",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:2a8f9787c6af6fe7:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
  "pid": 466594,
  "sha256": "d07a13370e4d6a6a6abdcfd76827ef7c0991362bd0043ae1f902898148c0a6fb",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:e37cae5c272f2a12:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
  "pid": 466594,
  "sha256": "c1d04af73990d492aeddeae1678948453dcb03afe9564782fafda521716fd66f",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:759cfb97b73257cf:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
  "pid": 466594,
  "sha256": "8ef6a5d57a020f215781ab0bc6a156213342dbd5f757c677fe270d0bad9c7795",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
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
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "context_path": "/tmp/native-trace-464967-1783994525919/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-464967-1783994525919/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 466594,
  "ppid": 466467,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC",
    "/target/debug/build/libc-8a22300c8f78b6db",
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
      "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-466594-1783994530796589811.map",
  "pid": 466594,
  "ppid": 466467,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-466594-1783994530796589811.map"
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 467155,
  "ppid": 467111,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:0bbd97097bb8927a:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
  "pid": 467155,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:abbe5db87215834f:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "0f9c4f2408120f88ef29a4be418eaec9f5af08444599b975f82290850c873d08",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:7b2b162e1adc5025:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "c67e989370cad068828d24f8df71b181504e0af21e563b287ca8e856e3ccd314",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:8bdd7ecdf8dcbc6a:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "9d9b043cdf2f933bf0177d391d660a3b3ab771958851400ce6ee41a32ba28fde",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:993a9f1e6c468a21:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "1193b67480859384232c6f782e12eaa50621495236d9d7f687bce075e3305b30",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:7ba1d03ac44ece34:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "7bc63d78f34d2785f2c829db3ccc45024dc37f3347aa1a2591c89eb9ea942b74",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:05bd2a4d4c327eaf:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "6c0e8722de9a7b36760d0c5fe63d90da40242772cca780d148138327f5505e09",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:4b6468c23ef4d4fb:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "6d5a6ef480466b09b8a3e1238064bc49d3d4238f6912abe81efbf7e8a5515c9a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:f39b34a667404eb9:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "4db162981c33b94b430bbd4b6a97d7402976fefaf068f02ab8ac831d697b9b6c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:7c82274bc185e7cb:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "871287dc3c2086fa9c7911c0ed0bced2387a435378f93aaf204621688fc18545",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:5d8b64a71ef92172:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "4c96b6e60d28c3a845153a9590367312d07aea3cf0473bfe46df7ab34387bd63",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:9a2363ea36cc88fe:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "fec7fd99a66753bdf90510e39bf8bddf58d65580e82883820598b7aa2b61240f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:03854211710fa78a:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "d250c848aa6aaa029602f47fb7f6fc2ddacfbc0cf3770c10918af1652b5d6c0a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "used:cc:499ddf9ac3dc8179:8f05523a0fa9857d:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
  "pid": 467155,
  "sha256": "beef5da5a6c1990c62ffa6870030b80fca74e235a45ee672440764f3d7b85ad9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
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
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "context_path": "/tmp/native-trace-464967-1783994525919/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-464967-1783994525919/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 467155,
  "ppid": 467111,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
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
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-467155-1783994532518387716.map",
  "pid": 467155,
  "ppid": 467111,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-467155-1783994532518387716.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "git",
    "submodule",
    "update",
    "--init"
  ],
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "exit_code": 128,
  "kind": "exec",
  "pid": 467215,
  "ppid": 467213,
  "success": false,
  "tool": "git",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 31

```json
{
  "acquisition_kind": "git_submodule",
  "argv": [
    "git",
    "submodule",
    "update",
    "--init"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "checkout_root": null,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "acq-ext:git:499ddf9ac3dc8179:e3b0c44298fc1c14",
  "exit_code": 128,
  "kind": "acquisition",
  "output": null,
  "pid": 467215,
  "success": false,
  "tool": "git",
  "url": null,
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 32

```json
{
  "argv": [
    "git",
    "submodule",
    "update",
    "--init"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "context_path": "/tmp/native-trace-464967-1783994525919/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "exit_code": 128,
  "host": "x86_64-unknown-linux-gnu",
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-464967-1783994525919/events/00000000-cargo-metadata.json",
  "num_jobs": "16",
  "opt_level": "0",
  "out_dir": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out",
  "pid": 467215,
  "ppid": 467213,
  "profile": "debug",
  "real_tool": "/usr/bin/git",
  "root_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "success": false,
  "target": "riscv64gc-unknown-linux-gnu",
  "tool": "git",
  "workspace_root": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 33

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

#### Record 34

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 1158,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1160,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "dom-0f2ae90e99c5bb61/build-script-build\n22.081  rustc            471248 469945   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cpp_demangle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n22.081  rust-lld         471250 471247   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQBSNHt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.093  collect2         471237 471236   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.097  cc               471249 471242   0 /usr/bin/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcpnC8lc/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.101  ld.lld           471255 471237   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc ...\n22.105  rust-lld         471255 471237   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.109  rustc            471243 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n22.110  collect2         471263 471249   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.120  cc               471265 470166   0 \n22.120  rustc            471260 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n22.132  ld.lld           471273 471263   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc ...\n22.132  rustc            471262 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n22.132  rust-lld         471273 471263   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.144  cc               471274 471265   0 /usr/bin/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcBTOL4I/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n22.146  cc               471269 470483   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcOywn2F/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.150  cross            471288 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n22.151  rustc            471308 471288   0 \n22.151  cc               471299 471269   0 /usr/bin/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcOywn2F/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.156  cc               471300 471037   0 /tmp/native-trace-469516-1783994548009/shims/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustctahcOs/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.160  rustc            471308 471288   0 /home/xmoe/.cargo/bin/rustc --print target-list /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n22.166  rustc            471270 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_sink --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n22.176  rustc            471277 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\")) -C metadata=f35517c6f15f2f68 ...\n22.176  cc               471333 471300   0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustctahcOs/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.178  rustc            471342 471288   0 /home/xmoe/.cargo/bin/rustc -vV\n22.185  rustc            471342 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.194  collect2         471341 471274   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.197  ld.lld           471357 471341   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378 ...\n22.201  rust-lld         471357 471341   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.202  cargo            471363 471288   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n22.212  cargo            471363 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n22.224  collect2         471394 471299   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWPcRyC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.229  rustc            471397 471363   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.242  ld.lld           471396 471394   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWPcRyC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60 ...\n22.251  rustc            471406 471363   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.269  rustc            471428 471363   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.300  rustc            471435 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_sink --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n22.300  runc             471454 464703   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c2 --log-format json --systemd-cgroup delete 0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c27f9db\n22.300  rust-lld         471396 471394   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWPcRyC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.301  rustc            471447 471288   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.301  runc             471439 464703   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c2 --log-format json --systemd-cgroup kill --all 0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c27f9db 9\n22.309  cc               471475 470217   0 /tmp/native-trace-469516-1783994548009/shims/cc -m64 /target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcYlBaPX/symbols.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n22.309  cc               471482 471475   0 /usr/bin/cc -m64 /target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcYlBaPX/symbols.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n22.309  rustc            471447 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.319  collect2         471483 471482   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7zmIYa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.341  docker           471489 471288   0 /usr/bin/docker --help\n22.363  rustc            471505 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_channel --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-channel-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n22.391  cross            471535 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n22.391  rustc            471537 471535   0 /home/xmoe/.cargo/bin/rustc --print target-list\n22.392  ld.lld           471484 471483   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7zmIYa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a ...\n22.395  collect2         471356 471333   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccClNIFa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.399  rustc            471510 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_task --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n22.405  rustc            471537 471535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n22.408  cc               471541 470355   0 /tmp/native-trace-469541-1783994548054/shims/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcjaYJTC/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.408  ld.lld           471546 471356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccClNIFa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911 ...\n22.411  cc               471551 471541   0 /usr/bin/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcjaYJTC/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.413  docker           471552 471288   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.413  build-script-bu  471500 469955   0 /target/debug/build/quote-c09a40bfdaa87378/build-script-build\n22.423  rustc            471571 471535   0 /home/xmoe/.cargo/bin/rustc -vV\n22.429  collect2         471585 471551   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBnzU3E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.431  rust-lld         471546 471356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccClNIFa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.432  rustc            471571 471535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.433  cross            471586 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n22.434  rustc            471590 471586   0 /home/xmoe/.cargo/bin/rustc --print target-list\n22.435  rustc            471534 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.103/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n22.436  rust-lld         471484 471483   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7zmIYa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.442  rustc            471590 471586   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n22.448  rustc            471561 471500   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n22.448  cargo            471603 471535   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n22.448  runc             471602 1599     0 /usr/bin/runc --version\n22.455  cargo            471603 471535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n22.459  rustc            471622 471586   0 /home/xmoe/.cargo/bin/rustc -vV\n22.459  docker-init      471621 1599     0 /usr/bin/docker-init --version\n22.461  docker           471624 471288   0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.474  cc               471619 470117   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcxFaI35/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.477  rustc            471622 471586   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.487  runc             471657 1599     0 /usr/bin/runc --version\n22.488  rustc            471660 471603   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.494  cc               471669 471619   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcxFaI35/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.506  cargo            471680 471586   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n22.506  docker-init      471681 1599     0 /usr/bin/docker-init --version\n22.510  collect2         471673 471669   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrelyz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.514  rustc            471696 471603   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.517  ld.lld           471697 471673   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrelyz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588 ...\n22.519  build-script-bu  471589 469955   0 /target/debug/build/getrandom-0f2ae90e99c5bb61/build-script-build\n22.520  cargo            471680 471586   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n22.521  rust-lld         471697 471673   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrelyz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.524  rustc            471679 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name semver --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.28/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n22.539  ld.lld           471600 471585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBnzU3E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc ...\n22.541  rustup           471712 471288   0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.542  rustc            471723 471603   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.544  rustc            471693 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name form_urlencoded --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/form_urlencoded-1.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n22.545  rustc            471732 471680   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.546  rust-lld         471600 471585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBnzU3E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.550  rustup           471733 471288   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.558  rustc            471752 471680   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.561  cc               471659 471062   0 /tmp/native-trace-469516-1783994548009/shims/cc -m64 /target/debug/build/zmij-3db3d55d935c9174/rustcySi6Jl/symbols.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.build_script_build.23d661728eba3fd8-cgu.0.rcgu.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.7omekk42uvw8sxwiratz4c561.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n22.577  rustc            471766 471680   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.588  rustc            471749 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.103/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n22.592  rustup           471770 471288   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n22.604  rustc            471672 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name itoa --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\")) -C metadata=3ec831c6786f21f8 ...\n22.617  rustc            471796 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n22.635  uname            471800 471288   0 /usr/bin/uname -r\n22.649  rustc            471753 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.103/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n22.655  containerd-shim  471807 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c27f9db -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c2 delete\n22.659  cc               471755 471659   0 /usr/bin/cc -m64 /target/debug/build/zmij-3db3d55d935c9174/rustcySi6Jl/symbols.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.build_script_build.23d661728eba3fd8-cgu.0.rcgu.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.7omekk42uvw8sxwiratz4c561.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n22.664  docker           471827 471288   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n22.671  sh               471819 2147557   0 /bin/sh -c which ps\n22.671  which            471819 2147557   0 /usr/bin/which ps\n22.671  sh               471837 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.671  collect2         471820 471755   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEQf4O5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.673  ps               471837 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.674  cc               471801 471179   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/zmij-3db3d55d935c9174/rustcTXGyX3/symbols.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.build_script_build.23d661728eba3fd8-cgu.0.rcgu.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.7omekk42uvw8sxwiratz4c561.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n22.675  cc               471839 471801   0 /usr/bin/cc -m64 /target/debug/build/zmij-3db3d55d935c9174/rustcTXGyX3/symbols.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.build_script_build.23d661728eba3fd8-cgu.0.rcgu.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.7omekk42uvw8sxwiratz4c561.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n22.684  collect2         471856 471839   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOvQX3t.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.691  ld.lld           471858 471856   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOvQX3t.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174 ...\n22.693  rust-lld         471858 471856   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOvQX3t.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.696  cc               471863 470562   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustczTppqj/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n"
}
```

#### Record 35

```json
{
  "argv": [
    "/target/debug/build/libc-8a22300c8f78b6db/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 466748,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
  "pid": 466748,
  "ppid": 466421,
  "root_cargo_pid": 466421,
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
  "_build_script_out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out"
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
  "build_script_root_pid": 466748,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 466751,
  "ppid": 466748,
  "root_cargo_pid": 466421,
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
  "_build_script_out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 37

```json
{
  "argv": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
  "pid": 467213,
  "ppid": 466421,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 38

```json
{
  "argv": [
    "/tmp/native-trace-464967-1783994525919/shims/git",
    "submodule",
    "update",
    "--init"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/tmp/native-trace-464967-1783994525919/shims/git",
  "pid": 467215,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 39

```json
{
  "argv": [
    "/usr/bin/git",
    "submodule",
    "update",
    "--init"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/usr/bin/git",
  "pid": 467216,
  "ppid": 467215,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 40

```json
{
  "argv": [
    "/usr/lib/git-core/git-submodule",
    "update",
    "--init"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git-submodule",
  "event": "process_exec",
  "image": "/usr/lib/git-core/git-submodule",
  "pid": 467232,
  "ppid": 467216,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 41

```json
{
  "argv": [
    "/usr/lib/git-core/git",
    "--exec-path"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/usr/lib/git-core/git",
  "pid": 467241,
  "ppid": 467232,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 42

```json
{
  "argv": [
    "/usr/bin/uname",
    "-s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "uname",
  "event": "process_exec",
  "image": "/usr/bin/uname",
  "pid": 467280,
  "ppid": 467232,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 43

```json
{
  "argv": [
    "/usr/lib/git-core/git",
    "rev-parse",
    "--git-dir"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/usr/lib/git-core/git",
  "pid": 467290,
  "ppid": 467232,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 44

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-E",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/1689630722408765815detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467291,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 45

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
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/1689630722408765815detect_compiler_family.c",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-dumpbase",
    "1689630722408765815detect_compiler_family.c",
    "-dumpbase-ext",
    ".c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467292,
  "ppid": 467291,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 46

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467293,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 47

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
    "-c",
    "brotli/common/dictionary.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467294,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 48

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/common/dictionary.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "e198953d800c79d4-dictionary.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467295,
  "ppid": 467294,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 49

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
    "/tmp/cc07qpiT.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467334,
  "ppid": 467294,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 50

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
    "-c",
    "brotli/dec/bit_reader.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467335,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 51

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/bit_reader.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-bit_reader.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467336,
  "ppid": 467335,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 52

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
    "/tmp/cc9X3Iiy.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467337,
  "ppid": 467335,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 53

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
    "-c",
    "brotli/dec/decode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467338,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 54

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/decode.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-decode.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467339,
  "ppid": 467338,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 55

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
    "/tmp/cc95t94S.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467353,
  "ppid": 467338,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 56

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
    "-c",
    "brotli/dec/huffman.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467355,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 57

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/huffman.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-huffman.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467356,
  "ppid": 467355,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 58

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
    "/tmp/ccBVYQQ5.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467359,
  "ppid": 467355,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 59

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
    "-c",
    "brotli/dec/state.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467360,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 60

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/state.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-state.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467362,
  "ppid": 467360,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 61

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
    "/tmp/ccV6XQud.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467365,
  "ppid": 467360,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 62

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
    "-c",
    "brotli/enc/backward_references.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467366,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 63

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/backward_references.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-backward_references.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467367,
  "ppid": 467366,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 64

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
    "/tmp/ccrktIIe.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467385,
  "ppid": 467366,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 65

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
    "-c",
    "brotli/enc/backward_references_hq.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467391,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 66

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/backward_references_hq.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-backward_references_hq.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467392,
  "ppid": 467391,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 67

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
    "/tmp/ccaD1Skt.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467408,
  "ppid": 467391,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 68

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
    "-c",
    "brotli/enc/bit_cost.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467414,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 69

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/bit_cost.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-bit_cost.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467416,
  "ppid": 467414,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 70

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
    "/tmp/cc3EcXen.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467423,
  "ppid": 467414,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 71

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
    "-c",
    "brotli/enc/block_splitter.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467425,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 72

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/block_splitter.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-block_splitter.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467426,
  "ppid": 467425,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 73

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
    "/tmp/cc0wabID.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467433,
  "ppid": 467425,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 74

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
    "-c",
    "brotli/enc/brotli_bit_stream.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467436,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 75

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/brotli_bit_stream.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-brotli_bit_stream.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467437,
  "ppid": 467436,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 76

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/tmp/ccLsJJqy.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467447,
  "ppid": 467436,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 77

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
    "-c",
    "brotli/enc/cluster.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467448,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 78

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/cluster.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-cluster.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467449,
  "ppid": 467448,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 79

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
    "/tmp/cc6fZGYO.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467450,
  "ppid": 467448,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 80

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
    "-c",
    "brotli/enc/compress_fragment.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467451,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 81

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/compress_fragment.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-compress_fragment.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467452,
  "ppid": 467451,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 82

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
    "/tmp/ccHNIzEC.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467459,
  "ppid": 467451,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 83

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "-c",
    "brotli/enc/compress_fragment_two_pass.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467463,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 84

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/compress_fragment_two_pass.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-compress_fragment_two_pass.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467464,
  "ppid": 467463,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 85

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/tmp/cc7wI7An.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467466,
  "ppid": 467463,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 86

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
    "-c",
    "brotli/enc/dictionary_hash.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467472,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 87

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/dictionary_hash.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-dictionary_hash.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467473,
  "ppid": 467472,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 88

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
    "/tmp/cc6vLa2U.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467477,
  "ppid": 467472,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 89

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
    "-c",
    "brotli/enc/encode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467478,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 90

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/encode.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-encode.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467480,
  "ppid": 467478,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 91

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
    "/tmp/ccqDvI7W.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467489,
  "ppid": 467478,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 92

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
    "-c",
    "brotli/enc/entropy_encode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467490,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 93

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/entropy_encode.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-entropy_encode.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467491,
  "ppid": 467490,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 94

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
    "/tmp/ccHomo7A.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467493,
  "ppid": 467490,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 95

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o",
    "-c",
    "brotli/enc/histogram.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467494,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 96

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/histogram.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-histogram.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467495,
  "ppid": 467494,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 97

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o",
    "/tmp/ccZvcoqW.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467498,
  "ppid": 467494,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 98

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o",
    "-c",
    "brotli/enc/literal_cost.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467499,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 99

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/literal_cost.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-literal_cost.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467500,
  "ppid": 467499,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 100

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o",
    "/tmp/ccH4vY28.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467504,
  "ppid": 467499,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 101

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o",
    "-c",
    "brotli/enc/memory.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467507,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 102

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/memory.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-memory.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467508,
  "ppid": 467507,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 103

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o",
    "/tmp/cc1l9i2A.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467512,
  "ppid": 467507,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 104

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o",
    "-c",
    "brotli/enc/metablock.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467513,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 105

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/metablock.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-metablock.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467514,
  "ppid": 467513,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 106

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o",
    "/tmp/ccRXWm55.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467518,
  "ppid": 467513,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 107

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o",
    "-c",
    "brotli/enc/static_dict.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467519,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 108

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/static_dict.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-static_dict.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467520,
  "ppid": 467519,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 109

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o",
    "/tmp/ccSLUSwl.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467521,
  "ppid": 467519,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 110

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o",
    "-c",
    "brotli/enc/utf8_util.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 467522,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 111

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/utf8_util.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-utf8_util.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 467523,
  "ppid": 467522,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 112

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o",
    "/tmp/ccuTSl42.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 467524,
  "ppid": 467522,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 113

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 467525,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 114

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "sD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467213,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 467526,
  "ppid": 467213,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 115

```json
{
  "crate": "brotli-sys",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "bsrun:5bb89c51dbce2eca:a68bd319a396e807:58281f166f704a4a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/build-script-build",
  "host": "x86_64-unknown-linux-gnu",
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "out_dir": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
  "success": true,
  "target": "riscv64gc-unknown-linux-gnu",
  "version": "0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  }
}
```

#### Record 116

```json
{
  "crate": "libc",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "bsrun:a733304fa0307800:4a171888d45fa12d:6ed0f36d8fdf2af7",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out",
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

#### Record 117

```json
{
  "crate": "brotli-sys",
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "event_id": "bsrun:5bb89c51dbce2eca:325298fb080efefc:70bcf1a2ee0afd48",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
  "success": true,
  "target": null,
  "version": "0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  }
}
```

#### Record 118

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 466748,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 466751,
  "ppid": 466748,
  "root_cargo_pid": 466421,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 119

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/common/dictionary.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "e198953d800c79d4-dictionary.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/common/dictionary.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467295,
  "ppid": 467294,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 120

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/bit_reader.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-bit_reader.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/dec/bit_reader.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467336,
  "ppid": 467335,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 121

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/decode.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-decode.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/dec/decode.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467339,
  "ppid": 467338,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 122

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/huffman.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-huffman.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/dec/huffman.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467356,
  "ppid": 467355,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 123

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/dec/state.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "76d4580618152496-state.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/dec/state.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467362,
  "ppid": 467360,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 124

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/backward_references.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-backward_references.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/backward_references.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467367,
  "ppid": 467366,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 125

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/backward_references_hq.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-backward_references_hq.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/backward_references_hq.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467392,
  "ppid": 467391,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 126

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/bit_cost.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-bit_cost.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/bit_cost.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467416,
  "ppid": 467414,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 127

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/block_splitter.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-block_splitter.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/block_splitter.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467426,
  "ppid": 467425,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 128

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/brotli_bit_stream.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-brotli_bit_stream.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/brotli_bit_stream.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467437,
  "ppid": 467436,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 129

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/cluster.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-cluster.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/cluster.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467449,
  "ppid": 467448,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 130

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/compress_fragment.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-compress_fragment.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/compress_fragment.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467452,
  "ppid": 467451,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 131

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/compress_fragment_two_pass.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-compress_fragment_two_pass.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/compress_fragment_two_pass.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467464,
  "ppid": 467463,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 132

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/dictionary_hash.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-dictionary_hash.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/dictionary_hash.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467473,
  "ppid": 467472,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 133

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/encode.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-encode.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/encode.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467480,
  "ppid": 467478,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 134

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/entropy_encode.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-entropy_encode.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/entropy_encode.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467491,
  "ppid": 467490,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 135

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/histogram.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-histogram.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/histogram.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467495,
  "ppid": 467494,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 136

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/literal_cost.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-literal_cost.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/literal_cost.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467500,
  "ppid": 467499,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 137

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/memory.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-memory.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/memory.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467508,
  "ppid": 467507,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 138

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/metablock.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-metablock.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/metablock.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467514,
  "ppid": 467513,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 139

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/static_dict.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-static_dict.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/static_dict.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467520,
  "ppid": 467519,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 140

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "brotli/enc/utf8_util.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
    "-dumpbase",
    "62394abbbe01bffa-utf8_util.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "brotli/enc/utf8_util.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467523,
  "ppid": 467522,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 141

```json
{
  "event": "archive",
  "tool": "/usr/bin/riscv64-linux-gnu-ar",
  "real_tool": "/usr/bin/riscv64-linux-gnu-ar",
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o",
    "..."
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": true,
  "pid": 467525,
  "ppid": 467213,
  "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466421,
  "build_script_root_pid": 467213,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:02:33.956163+00:00",
  "crate": "brotli-sys",
  "version": "0.3.2",
  "architecture": "riscv64",
  "duration_seconds": 33.298928363248706,
  "trace_record_count": 117,
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
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "manifest_path": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/Cargo.toml"
      }
    ],
    "attributed_event_count": 35,
    "unattributed_event_count": 82,
    "owners": [
      {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "event_count": 24,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 2,
          "used_input": 14,
          "link": 1,
          "exec_context": 2,
          "resolved_link": 1,
          "acquisition": 1,
          "build_script_run": 2
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
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "workspace_root": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
          "name": "brotli-sys",
          "version": "0.3.2",
          "manifest_path": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2"
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
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "kind": "exec",
      "pid": 466594,
      "ppid": 466467,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:1190eb007d799be2:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
      "pid": 466594,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:c5eb16742d92300e:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
      "pid": 466594,
      "sha256": "750e5b687b769ef8e1f6a9de3b3b4cc39d771526f669d42b53a924666b856dae",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:135ba558c9da774d:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
      "pid": 466594,
      "sha256": "53140dc43536033138eb06a34e55a6a0ff33641d1e3937f2ad7a716aa3ee683a",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:2a8f9787c6af6fe7:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
      "pid": 466594,
      "sha256": "d07a13370e4d6a6a6abdcfd76827ef7c0991362bd0043ae1f902898148c0a6fb",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:e37cae5c272f2a12:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
      "pid": 466594,
      "sha256": "c1d04af73990d492aeddeae1678948453dcb03afe9564782fafda521716fd66f",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:759cfb97b73257cf:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
      "pid": 466594,
      "sha256": "8ef6a5d57a020f215781ab0bc6a156213342dbd5f757c677fe270d0bad9c7795",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
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
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "context_path": "/tmp/native-trace-464967-1783994525919/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-464967-1783994525919/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 466594,
      "ppid": 466467,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC",
        "/target/debug/build/libc-8a22300c8f78b6db",
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
          "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcVDgJjC/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-466594-1783994530796589811.map",
      "pid": 466594,
      "ppid": 466467,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-466594-1783994530796589811.map"
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 467155,
      "ppid": 467111,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:0bbd97097bb8927a:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
      "pid": 467155,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:abbe5db87215834f:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "0f9c4f2408120f88ef29a4be418eaec9f5af08444599b975f82290850c873d08",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:7b2b162e1adc5025:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "c67e989370cad068828d24f8df71b181504e0af21e563b287ca8e856e3ccd314",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:8bdd7ecdf8dcbc6a:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "9d9b043cdf2f933bf0177d391d660a3b3ab771958851400ce6ee41a32ba28fde",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:993a9f1e6c468a21:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "1193b67480859384232c6f782e12eaa50621495236d9d7f687bce075e3305b30",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:7ba1d03ac44ece34:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "7bc63d78f34d2785f2c829db3ccc45024dc37f3347aa1a2591c89eb9ea942b74",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:05bd2a4d4c327eaf:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "6c0e8722de9a7b36760d0c5fe63d90da40242772cca780d148138327f5505e09",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:4b6468c23ef4d4fb:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "6d5a6ef480466b09b8a3e1238064bc49d3d4238f6912abe81efbf7e8a5515c9a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:f39b34a667404eb9:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "4db162981c33b94b430bbd4b6a97d7402976fefaf068f02ab8ac831d697b9b6c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:7c82274bc185e7cb:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "871287dc3c2086fa9c7911c0ed0bced2387a435378f93aaf204621688fc18545",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:5d8b64a71ef92172:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "4c96b6e60d28c3a845153a9590367312d07aea3cf0473bfe46df7ab34387bd63",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:9a2363ea36cc88fe:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "fec7fd99a66753bdf90510e39bf8bddf58d65580e82883820598b7aa2b61240f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:03854211710fa78a:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "d250c848aa6aaa029602f47fb7f6fc2ddacfbc0cf3770c10918af1652b5d6c0a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "used:cc:499ddf9ac3dc8179:8f05523a0fa9857d:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
      "pid": 467155,
      "sha256": "beef5da5a6c1990c62ffa6870030b80fca74e235a45ee672440764f3d7b85ad9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
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
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "context_path": "/tmp/native-trace-464967-1783994525919/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-464967-1783994525919/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 467155,
      "ppid": 467111,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
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
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcYzio3X/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.0lwb3w1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.0lwb3w1.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-467155-1783994532518387716.map",
      "pid": 467155,
      "ppid": 467111,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-467155-1783994532518387716.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "git",
        "submodule",
        "update",
        "--init"
      ],
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "exit_code": 128,
      "kind": "exec",
      "pid": 467215,
      "ppid": 467213,
      "success": false,
      "tool": "git",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "acquisition_kind": "git_submodule",
      "argv": [
        "git",
        "submodule",
        "update",
        "--init"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "checkout_root": null,
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "acq-ext:git:499ddf9ac3dc8179:e3b0c44298fc1c14",
      "exit_code": 128,
      "kind": "acquisition",
      "output": null,
      "pid": 467215,
      "success": false,
      "tool": "git",
      "url": null,
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "git",
        "submodule",
        "update",
        "--init"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "context_path": "/tmp/native-trace-464967-1783994525919/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "exit_code": 128,
      "host": "x86_64-unknown-linux-gnu",
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-464967-1783994525919/events/00000000-cargo-metadata.json",
      "num_jobs": "16",
      "opt_level": "0",
      "out_dir": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out",
      "pid": 467215,
      "ppid": 467213,
      "profile": "debug",
      "real_tool": "/usr/bin/git",
      "root_cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "success": false,
      "target": "riscv64gc-unknown-linux-gnu",
      "tool": "git",
      "workspace_root": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
      "parsed_event_count": 1158,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1160,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "dom-0f2ae90e99c5bb61/build-script-build\n22.081  rustc            471248 469945   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cpp_demangle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n22.081  rust-lld         471250 471247   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQBSNHt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.093  collect2         471237 471236   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.097  cc               471249 471242   0 /usr/bin/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcpnC8lc/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.101  ld.lld           471255 471237   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc ...\n22.105  rust-lld         471255 471237   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.109  rustc            471243 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n22.110  collect2         471263 471249   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.120  cc               471265 470166   0 \n22.120  rustc            471260 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n22.132  ld.lld           471273 471263   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc ...\n22.132  rustc            471262 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n22.132  rust-lld         471273 471263   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.144  cc               471274 471265   0 /usr/bin/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcBTOL4I/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n22.146  cc               471269 470483   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcOywn2F/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.150  cross            471288 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n22.151  rustc            471308 471288   0 \n22.151  cc               471299 471269   0 /usr/bin/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcOywn2F/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.156  cc               471300 471037   0 /tmp/native-trace-469516-1783994548009/shims/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustctahcOs/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.160  rustc            471308 471288   0 /home/xmoe/.cargo/bin/rustc --print target-list /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n22.166  rustc            471270 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_sink --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n22.176  rustc            471277 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\")) -C metadata=f35517c6f15f2f68 ...\n22.176  cc               471333 471300   0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustctahcOs/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.178  rustc            471342 471288   0 /home/xmoe/.cargo/bin/rustc -vV\n22.185  rustc            471342 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.194  collect2         471341 471274   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.197  ld.lld           471357 471341   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378 ...\n22.201  rust-lld         471357 471341   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.202  cargo            471363 471288   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n22.212  cargo            471363 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n22.224  collect2         471394 471299   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWPcRyC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.229  rustc            471397 471363   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.242  ld.lld           471396 471394   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWPcRyC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60 ...\n22.251  rustc            471406 471363   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.269  rustc            471428 471363   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.300  rustc            471435 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_sink --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n22.300  runc             471454 464703   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c2 --log-format json --systemd-cgroup delete 0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c27f9db\n22.300  rust-lld         471396 471394   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWPcRyC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.301  rustc            471447 471288   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.301  runc             471439 464703   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c2 --log-format json --systemd-cgroup kill --all 0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c27f9db 9\n22.309  cc               471475 470217   0 /tmp/native-trace-469516-1783994548009/shims/cc -m64 /target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcYlBaPX/symbols.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n22.309  cc               471482 471475   0 /usr/bin/cc -m64 /target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcYlBaPX/symbols.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n22.309  rustc            471447 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.319  collect2         471483 471482   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7zmIYa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.341  docker           471489 471288   0 /usr/bin/docker --help\n22.363  rustc            471505 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_channel --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-channel-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n22.391  cross            471535 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n22.391  rustc            471537 471535   0 /home/xmoe/.cargo/bin/rustc --print target-list\n22.392  ld.lld           471484 471483   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7zmIYa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a ...\n22.395  collect2         471356 471333   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccClNIFa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.399  rustc            471510 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_task --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n22.405  rustc            471537 471535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n22.408  cc               471541 470355   0 /tmp/native-trace-469541-1783994548054/shims/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcjaYJTC/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.408  ld.lld           471546 471356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccClNIFa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911 ...\n22.411  cc               471551 471541   0 /usr/bin/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcjaYJTC/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.413  docker           471552 471288   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.413  build-script-bu  471500 469955   0 /target/debug/build/quote-c09a40bfdaa87378/build-script-build\n22.423  rustc            471571 471535   0 /home/xmoe/.cargo/bin/rustc -vV\n22.429  collect2         471585 471551   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBnzU3E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.431  rust-lld         471546 471356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccClNIFa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.432  rustc            471571 471535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.433  cross            471586 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n22.434  rustc            471590 471586   0 /home/xmoe/.cargo/bin/rustc --print target-list\n22.435  rustc            471534 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.103/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n22.436  rust-lld         471484 471483   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7zmIYa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.442  rustc            471590 471586   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n22.448  rustc            471561 471500   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n22.448  cargo            471603 471535   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n22.448  runc             471602 1599     0 /usr/bin/runc --version\n22.455  cargo            471603 471535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n22.459  rustc            471622 471586   0 /home/xmoe/.cargo/bin/rustc -vV\n22.459  docker-init      471621 1599     0 /usr/bin/docker-init --version\n22.461  docker           471624 471288   0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.474  cc               471619 470117   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcxFaI35/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.477  rustc            471622 471586   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.487  runc             471657 1599     0 /usr/bin/runc --version\n22.488  rustc            471660 471603   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.494  cc               471669 471619   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcxFaI35/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n22.506  cargo            471680 471586   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n22.506  docker-init      471681 1599     0 /usr/bin/docker-init --version\n22.510  collect2         471673 471669   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrelyz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.514  rustc            471696 471603   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.517  ld.lld           471697 471673   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrelyz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588 ...\n22.519  build-script-bu  471589 469955   0 /target/debug/build/getrandom-0f2ae90e99c5bb61/build-script-build\n22.520  cargo            471680 471586   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n22.521  rust-lld         471697 471673   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrelyz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.524  rustc            471679 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name semver --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.28/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n22.539  ld.lld           471600 471585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBnzU3E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc ...\n22.541  rustup           471712 471288   0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.542  rustc            471723 471603   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.544  rustc            471693 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name form_urlencoded --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/form_urlencoded-1.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n22.545  rustc            471732 471680   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.546  rust-lld         471600 471585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBnzU3E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.550  rustup           471733 471288   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.558  rustc            471752 471680   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.561  cc               471659 471062   0 /tmp/native-trace-469516-1783994548009/shims/cc -m64 /target/debug/build/zmij-3db3d55d935c9174/rustcySi6Jl/symbols.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.build_script_build.23d661728eba3fd8-cgu.0.rcgu.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.7omekk42uvw8sxwiratz4c561.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n22.577  rustc            471766 471680   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.588  rustc            471749 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.103/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n22.592  rustup           471770 471288   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n22.604  rustc            471672 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name itoa --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\")) -C metadata=3ec831c6786f21f8 ...\n22.617  rustc            471796 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n22.635  uname            471800 471288   0 /usr/bin/uname -r\n22.649  rustc            471753 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.103/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n22.655  containerd-shim  471807 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c27f9db -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0dde36b1ec1b893322aebb0263e96d01dfc5a0019da8f7dde7c7767d9c2 delete\n22.659  cc               471755 471659   0 /usr/bin/cc -m64 /target/debug/build/zmij-3db3d55d935c9174/rustcySi6Jl/symbols.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.build_script_build.23d661728eba3fd8-cgu.0.rcgu.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.7omekk42uvw8sxwiratz4c561.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n22.664  docker           471827 471288   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n22.671  sh               471819 2147557   0 /bin/sh -c which ps\n22.671  which            471819 2147557   0 /usr/bin/which ps\n22.671  sh               471837 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.671  collect2         471820 471755   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEQf4O5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.673  ps               471837 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.674  cc               471801 471179   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/zmij-3db3d55d935c9174/rustcTXGyX3/symbols.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.build_script_build.23d661728eba3fd8-cgu.0.rcgu.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.7omekk42uvw8sxwiratz4c561.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n22.675  cc               471839 471801   0 /usr/bin/cc -m64 /target/debug/build/zmij-3db3d55d935c9174/rustcTXGyX3/symbols.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.build_script_build.23d661728eba3fd8-cgu.0.rcgu.o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174.7omekk42uvw8sxwiratz4c561.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n22.684  collect2         471856 471839   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOvQX3t.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.691  ld.lld           471858 471856   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOvQX3t.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/zmij-3db3d55d935c9174/build_script_build-3db3d55d935c9174 ...\n22.693  rust-lld         471858 471856   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOvQX3t.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n22.696  cc               471863 470562   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustczTppqj/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-8a22300c8f78b6db/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 466748,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
      "pid": 466748,
      "ppid": 466421,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 466748,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 466751,
      "ppid": 466748,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
      "pid": 467213,
      "ppid": 466421,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/tmp/native-trace-464967-1783994525919/shims/git",
        "submodule",
        "update",
        "--init"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/tmp/native-trace-464967-1783994525919/shims/git",
      "pid": 467215,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/git",
        "submodule",
        "update",
        "--init"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/usr/bin/git",
      "pid": 467216,
      "ppid": 467215,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/git-core/git-submodule",
        "update",
        "--init"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git-submodule",
      "event": "process_exec",
      "image": "/usr/lib/git-core/git-submodule",
      "pid": 467232,
      "ppid": 467216,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/git-core/git",
        "--exec-path"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/usr/lib/git-core/git",
      "pid": 467241,
      "ppid": 467232,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/uname",
        "-s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "uname",
      "event": "process_exec",
      "image": "/usr/bin/uname",
      "pid": 467280,
      "ppid": 467232,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/git-core/git",
        "rev-parse",
        "--git-dir"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/usr/lib/git-core/git",
      "pid": 467290,
      "ppid": 467232,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-E",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/1689630722408765815detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467291,
      "ppid": 467213,
      "root_cargo_pid": 466421,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/1689630722408765815detect_compiler_family.c",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-dumpbase",
        "1689630722408765815detect_compiler_family.c",
        "-dumpbase-ext",
        ".c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467292,
      "ppid": 467291,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467293,
      "ppid": 467213,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
        "-c",
        "brotli/common/dictionary.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467294,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/common/dictionary.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "e198953d800c79d4-dictionary.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467295,
      "ppid": 467294,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
        "/tmp/cc07qpiT.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467334,
      "ppid": 467294,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
        "-c",
        "brotli/dec/bit_reader.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467335,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/dec/bit_reader.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "76d4580618152496-bit_reader.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467336,
      "ppid": 467335,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
        "/tmp/cc9X3Iiy.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467337,
      "ppid": 467335,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
        "-c",
        "brotli/dec/decode.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467338,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/dec/decode.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "76d4580618152496-decode.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467339,
      "ppid": 467338,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
        "/tmp/cc95t94S.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467353,
      "ppid": 467338,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
        "-c",
        "brotli/dec/huffman.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467355,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/dec/huffman.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "76d4580618152496-huffman.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467356,
      "ppid": 467355,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
        "/tmp/ccBVYQQ5.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467359,
      "ppid": 467355,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
        "-c",
        "brotli/dec/state.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467360,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/dec/state.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "76d4580618152496-state.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467362,
      "ppid": 467360,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
        "/tmp/ccV6XQud.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467365,
      "ppid": 467360,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
        "-c",
        "brotli/enc/backward_references.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467366,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/backward_references.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-backward_references.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467367,
      "ppid": 467366,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
        "/tmp/ccrktIIe.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467385,
      "ppid": 467366,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
        "-c",
        "brotli/enc/backward_references_hq.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467391,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/backward_references_hq.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-backward_references_hq.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467392,
      "ppid": 467391,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
        "/tmp/ccaD1Skt.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467408,
      "ppid": 467391,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
        "-c",
        "brotli/enc/bit_cost.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467414,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/bit_cost.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-bit_cost.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467416,
      "ppid": 467414,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
        "/tmp/cc3EcXen.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467423,
      "ppid": 467414,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
        "-c",
        "brotli/enc/block_splitter.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467425,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/block_splitter.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-block_splitter.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467426,
      "ppid": 467425,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
        "/tmp/cc0wabID.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467433,
      "ppid": 467425,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
        "-c",
        "brotli/enc/brotli_bit_stream.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467436,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/brotli_bit_stream.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-brotli_bit_stream.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467437,
      "ppid": 467436,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
        "/tmp/ccLsJJqy.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467447,
      "ppid": 467436,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
        "-c",
        "brotli/enc/cluster.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467448,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/cluster.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-cluster.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467449,
      "ppid": 467448,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
        "/tmp/cc6fZGYO.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467450,
      "ppid": 467448,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
        "-c",
        "brotli/enc/compress_fragment.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467451,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/compress_fragment.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-compress_fragment.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467452,
      "ppid": 467451,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
        "/tmp/ccHNIzEC.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467459,
      "ppid": 467451,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
        "-c",
        "brotli/enc/compress_fragment_two_pass.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467463,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/compress_fragment_two_pass.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-compress_fragment_two_pass.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467464,
      "ppid": 467463,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
        "/tmp/cc7wI7An.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467466,
      "ppid": 467463,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
        "-c",
        "brotli/enc/dictionary_hash.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467472,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/dictionary_hash.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-dictionary_hash.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467473,
      "ppid": 467472,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
        "/tmp/cc6vLa2U.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467477,
      "ppid": 467472,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
        "-c",
        "brotli/enc/encode.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467478,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/encode.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-encode.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467480,
      "ppid": 467478,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
        "/tmp/ccqDvI7W.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467489,
      "ppid": 467478,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
        "-c",
        "brotli/enc/entropy_encode.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467490,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/entropy_encode.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-entropy_encode.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467491,
      "ppid": 467490,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
        "/tmp/ccHomo7A.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467493,
      "ppid": 467490,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o",
        "-c",
        "brotli/enc/histogram.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467494,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/histogram.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-histogram.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467495,
      "ppid": 467494,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o",
        "/tmp/ccZvcoqW.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467498,
      "ppid": 467494,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o",
        "-c",
        "brotli/enc/literal_cost.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467499,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/literal_cost.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-literal_cost.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467500,
      "ppid": 467499,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o",
        "/tmp/ccH4vY28.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467504,
      "ppid": 467499,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o",
        "-c",
        "brotli/enc/memory.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467507,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/memory.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-memory.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467508,
      "ppid": 467507,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o",
        "/tmp/cc1l9i2A.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467512,
      "ppid": 467507,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o",
        "-c",
        "brotli/enc/metablock.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467513,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/metablock.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-metablock.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467514,
      "ppid": 467513,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o",
        "/tmp/ccRXWm55.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467518,
      "ppid": 467513,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o",
        "-c",
        "brotli/enc/static_dict.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467519,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/static_dict.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-static_dict.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467520,
      "ppid": 467519,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o",
        "/tmp/ccSLUSwl.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467521,
      "ppid": 467519,
      "root_cargo_pid": 466421,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o",
        "-c",
        "brotli/enc/utf8_util.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 467522,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "brotli/enc/utf8_util.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/",
        "-dumpbase",
        "62394abbbe01bffa-utf8_util.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 467523,
      "ppid": 467522,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o",
        "/tmp/ccuTSl42.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 467524,
      "ppid": 467522,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "cqD",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 467525,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "sD",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467213,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 467526,
      "ppid": 467213,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "brotli-sys",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "bsrun:5bb89c51dbce2eca:a68bd319a396e807:58281f166f704a4a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/build-script-build",
      "host": "x86_64-unknown-linux-gnu",
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "out_dir": "/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
      "success": true,
      "target": "riscv64gc-unknown-linux-gnu",
      "version": "0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "libc",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "bsrun:a733304fa0307800:4a171888d45fa12d:6ed0f36d8fdf2af7",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out",
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
      "crate": "brotli-sys",
      "cwd": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "event_id": "bsrun:5bb89c51dbce2eca:325298fb080efefc:70bcf1a2ee0afd48",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
      "out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
      "success": true,
      "target": null,
      "version": "0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2",
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
      "build_script_root_pid": 466748,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 466751,
      "ppid": 466748,
      "root_cargo_pid": 466421,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 1992,
    "crate": "brotli-sys",
    "version": "0.3.2",
    "crate_id": "4566",
    "version_id": "65780",
    "downloads": 7258982,
    "cumulative_downloads": 101677447474,
    "cumulative_share_of_global": 0.3801485032752649,
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
