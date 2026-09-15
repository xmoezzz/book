# `brotli-sys` `0.3.2`

Platform: Linux ppc64le

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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "acq-ext:git:f4938bb327a0e643:e3b0c44298fc1c14",
  "exit_code": 128,
  "kind": "acquisition",
  "output": null,
  "pid": 467310,
  "success": false,
  "tool": "git",
  "url": null,
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/usr/bin/git",
  "pid": 467311,
  "ppid": 467310,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
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
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-467240-1783994532687417057.map",
  "pid": 467240,
  "ppid": 467199,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-467240-1783994532687417057.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a`

Owner: `brotli-sys` `0.3.2`

### Source files

* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/common/dictionary.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/bit_reader.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/decode.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/huffman.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/state.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/backward_references.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/backward_references_hq.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/bit_cost.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/block_splitter.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/brotli_bit_stream.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/cluster.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/compress_fragment.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/compress_fragment_two_pass.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/dictionary_hash.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/encode.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/entropy_encode.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc/histogram.c`

### Source acquisition records

_None._

### Source preparation records

#### Record 1

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
    "-c",
    "brotli/common/dictionary.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467332,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 2

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
    "-c",
    "brotli/dec/bit_reader.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467348,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 3

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
    "-c",
    "brotli/dec/decode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467351,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 4

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
    "-c",
    "brotli/dec/huffman.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467357,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 5

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
    "-c",
    "brotli/dec/state.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467363,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 6

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
    "-c",
    "brotli/enc/backward_references.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467369,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 7

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
    "-c",
    "brotli/enc/backward_references_hq.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467382,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 8

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
    "-c",
    "brotli/enc/bit_cost.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467397,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 9

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
    "-c",
    "brotli/enc/block_splitter.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467404,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 10

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
    "-c",
    "brotli/enc/brotli_bit_stream.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467427,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 11

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
    "-c",
    "brotli/enc/cluster.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467439,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 12

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
    "-c",
    "brotli/enc/compress_fragment.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467445,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 13

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "-c",
    "brotli/enc/compress_fragment_two_pass.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467454,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 14

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
    "-c",
    "brotli/enc/dictionary_hash.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467457,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 15

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
    "-c",
    "brotli/enc/encode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467461,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 16

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
    "-c",
    "brotli/enc/entropy_encode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467467,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 17

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
    "-c",
    "brotli/enc/histogram.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467470,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/backward_references.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "backward_references.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/backward_references.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467370,
  "ppid": 467369,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 2

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/bit_reader.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "bit_reader.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/dec/bit_reader.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467349,
  "ppid": 467348,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 3

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/huffman.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "huffman.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/dec/huffman.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467358,
  "ppid": 467357,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 4

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/backward_references_hq.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "backward_references_hq.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/backward_references_hq.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467383,
  "ppid": 467382,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 5

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/brotli_bit_stream.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "brotli_bit_stream.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/brotli_bit_stream.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467428,
  "ppid": 467427,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 6

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/entropy_encode.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "entropy_encode.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/entropy_encode.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467468,
  "ppid": 467467,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 7

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/block_splitter.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "block_splitter.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/block_splitter.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467405,
  "ppid": 467404,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 8

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/dictionary_hash.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "dictionary_hash.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/dictionary_hash.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467458,
  "ppid": 467457,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 9

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/encode.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "encode.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/encode.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467462,
  "ppid": 467461,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 10

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/compress_fragment_two_pass.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "compress_fragment_two_pass.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/compress_fragment_two_pass.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467455,
  "ppid": 467454,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 11

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/decode.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "decode.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/dec/decode.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467352,
  "ppid": 467351,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 12

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/common/dictionary.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "dictionary.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/common/dictionary.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467333,
  "ppid": 467332,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 13

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/bit_cost.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "bit_cost.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/bit_cost.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467399,
  "ppid": 467397,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 14

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/compress_fragment.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "compress_fragment.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/compress_fragment.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467446,
  "ppid": 467445,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 15

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/cluster.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "cluster.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/cluster.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467440,
  "ppid": 467439,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 16

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/state.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "state.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/dec/state.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467364,
  "ppid": 467363,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 17

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/histogram.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "histogram.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/histogram.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467471,
  "ppid": 467470,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
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
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
    "..."
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": true,
  "pid": 467502,
  "ppid": 467309,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "workspace_root": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
      "name": "brotli-sys",
      "version": "0.3.2",
      "manifest_path": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2"
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
  "pid": 466795,
  "ppid": 466586,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
  "event_id": "used:cc:f7a275179e4f3c0d:85334527128be1aa:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
  "pid": 466795,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
  "pid": 466795,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
  "pid": 466795,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
  "pid": 466795,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
  "pid": 466795,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
  "pid": 466795,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
  "context_path": "/tmp/native-trace-465204-1783994526290/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-465204-1783994526290/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 466795,
  "ppid": 466586,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI",
    "/target/debug/build/libc-8a22300c8f78b6db",
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
      "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-466795-1783994531201141717.map",
  "pid": 466795,
  "ppid": 466586,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-466795-1783994531201141717.map"
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 467240,
  "ppid": 467199,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:7dcb2d8a395fa908:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
  "pid": 467240,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:3d3e98fbfacbd8c8:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "16a2c17da7dc95004490408657f8fc8243816ef6c99f809aeabc2d3b0e450be0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:69f2bc9c8244f2ed:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "28e7b5345900b77133ccbde03bb90a8c252fdd2b219ac6d30bce8481f0e40d17",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:399f8993f7acad1e:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "8b1948f692583a53faaa88cfa2c959be8e62dd848f0de0a62c5ca4307336746b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:a847d8b98a67505d:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "05311048b1d145f9b84b194bd49dcaa0be5f02eb709d9854f5c0c088502d0bfc",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:d29c4dece0ce2bd2:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "39a340bec4512c8ca2c8d3a4b1e841bbbad763009bf855f326057fd10d745537",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:7c2c3f75c52e67ee:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "587858f6817770d208be6f4191d9acb3904f4929feef568dc7fdc6ad57735d58",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:2bff78ba64bc3569:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "8bfa8688a1ef2c99e47a8176dcfcd6ca37d6ac7cfa47087cf2095c5ef97fb0c3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:d9b2673402ce23f5:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "a3028a0f117de5c5f124e24542cf1a688400e97adc9061c54f9f643d178c4df1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:a9918a0008e8e763:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "a59ce9021114960dad3b04ffaa0b17d40729b09be7b27a5d2fe84bffb69faccd",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:6e2578c54ab59c48:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "da117242e0b61f84c7e3be8c39c921ceb601b0e64670dddffb9f75eaec7f150f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:67df60076ef24811:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "3558f8f79dd4adca90cc9cabeb4edd6c2bdfc0d267b2387822e5989d0c99b679",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:9503a4e0d00d645f:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "bcc417cd39f195a546acad7ad52bd90ba2c30aec12a6c78a266ec9ccae840dc9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f4938bb327a0e643:c55467279ba7a335:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
  "pid": 467240,
  "sha256": "beef5da5a6c1990c62ffa6870030b80fca74e235a45ee672440764f3d7b85ad9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "context_path": "/tmp/native-trace-465204-1783994526290/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-465204-1783994526290/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 467240,
  "ppid": 467199,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
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
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-467240-1783994532687417057.map",
  "pid": 467240,
  "ppid": 467199,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-467240-1783994532687417057.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "exit_code": 128,
  "kind": "exec",
  "pid": 467310,
  "ppid": 467309,
  "success": false,
  "tool": "git",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "acq-ext:git:f4938bb327a0e643:e3b0c44298fc1c14",
  "exit_code": 128,
  "kind": "acquisition",
  "output": null,
  "pid": 467310,
  "success": false,
  "tool": "git",
  "url": null,
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "context_path": "/tmp/native-trace-465204-1783994526290/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "exit_code": 128,
  "host": "x86_64-unknown-linux-gnu",
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-465204-1783994526290/events/00000000-cargo-metadata.json",
  "num_jobs": "16",
  "opt_level": "0",
  "out_dir": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out",
  "pid": 467310,
  "ppid": 467309,
  "profile": "debug",
  "real_tool": "/usr/bin/git",
  "root_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "success": false,
  "target": "powerpc64le-unknown-linux-gnu",
  "tool": "git",
  "workspace_root": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "parse_error_count": 1,
  "parsed_event_count": 1054,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1055,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "u/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.460  cc               471033 470028   0 /tmp/native-trace-469308-1783994547847/shims/cc -m64 /target/debug/build/libc-08068d25dbed1dac/rustcp8SYR5/symbols.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n21.461  cc               471036 471033   0 /usr/bin/cc -m64 /target/debug/build/libc-08068d25dbed1dac/rustcp8SYR5/symbols.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n21.466  cc               471035 471031   0 /usr/bin/cc -m64 /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/rustckwrFQ6/symbols.o /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/build_script_build-3c1e0afe26da35f6.build_script_build.db007148713b585a /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/build_script_build-3c1e0afe26da35f6.73wwo9hmpn5ysmjykv0131bih.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.472  collect2         471040 471035   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZUAk0E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.473  ld.lld           471042 471040   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZUAk0E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/build_script_build-3c1e0afe26da35f6 ...\n21.474  rust-lld         471042 471040   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZUAk0E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.475  rustup           471043 460320   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n21.481  build-script-bu  470997 469950   0 /target/debug/build/getrandom-0f2ae90e99c5bb61/build-script-build\n21.481  rustc            471037 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n21.482  build-script-bu  471032 469960   0 /target/debug/build/icu_properties_data-bb5269ffc4712489/build-script-build\n21.490  collect2         471048 471036   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgKSfEL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.494  ld.lld           471056 471048   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgKSfEL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac ...\n21.499  rust-lld         471056 471048   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgKSfEL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.518  build-script-bu  471061 469955   0 /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/build-script-build\n21.530  rustc            471084 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.539  rustc            471062 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\")) -C metadata=f35517c6f15f2f68 ...\n21.541  build-script-bu  471106 469917   0 /target/debug/build/cpp_demangle-bdc218a092b7c581/build-script-build\n21.552  rustc            471110 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n21.560  cc               471108 470040   0 /tmp/native-trace-469275-1783994547789/shims/cc -m64 /target/debug/build/cpp_demangle-bdc218a092b7c581/rustcrN9wN5/symbols.o /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n21.561  cc               471117 471108   0 /usr/bin/cc -m64 /target/debug/build/cpp_demangle-bdc218a092b7c581/rustcrN9wN5/symbols.o /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n21.566  rustc            471119 469917   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cpp_demangle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n21.571  collect2         471124 471117   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu62cNN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.576  ld.lld           471127 471124   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu62cNN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581 ...\n21.582  rustc            471128 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.583  rust-lld         471127 471124   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu62cNN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.595  rustc            471126 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.599  rustc            471038 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name percent_encoding --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/percent-encoding-2.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n21.605  build-script-bu  471080 469950   0 /target/debug/build/icu_properties_data-bb5269ffc4712489/build-script-build\n21.626  rustc            471102 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.639  rustc            471169 469945   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.647  build-script-bu  471173 469917   0 /target/debug/build/libc-08068d25dbed1dac/build-script-build\n21.652  rustc            471174 471173   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n21.656  rustc            471172 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_io --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n21.663  cc               471170 470381   0 /tmp/native-trace-469541-1783994548054/shims/cc -m64 /target/debug/build/getrandom-0f2ae90e99c5bb61/rustcXAbwQ5/symbols.o /target/debug/build/getrandom-0f2ae90e99c5bb61/build_script_build-0f2ae90e99c5bb61.build_script_build.cc6c5348da4bd5ff-cgu.0.rcg /target/debug/build/getrandom-0f2ae90e99c5bb61/build_script_build-0f2ae90e99c5bb61.78giule9cmi5xz3xntrc0616a.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.681  rustc            471145 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.681  rustc            471182 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_io --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n21.682  rustc            471184 469917   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.691  rustc            471179 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\")) -C metadata=f35517c6f15f2f68 ...\n21.694  build-script-bu  471190 469950   0 /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/build-script-build\n21.712  cc               471196 470379   0 /tmp/native-trace-469541-1783994548054/shims/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcZwovwi/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.718  rustc            471204 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_sink --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n21.727  cc               471210 471196   0 /usr/bin/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcZwovwi/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.745  cc               471233 470167   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcXdm63b/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.764  cc               471236 471233   0 /usr/bin/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcXdm63b/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.777  build-script-bu  471239 469945   0 /target/debug/build/cpp_demangle-bdc218a092b7c581/build-script-build\n21.783  cc               471242 470227   0 /tmp/native-trace-469516-1783994548009/shims/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcpnC8lc/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.785  rustc            471211 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.791  cc               471205 471170   0 /usr/bin/cc -m64 /target/debug/build/getrandom-0f2ae90e99c5bb61/rustcXAbwQ5/symbols.o /target/debug/build/getrandom-0f2ae90e99c5bb61/build_script_build-0f2ae90e99c5bb61.build_script_build.cc6c5348da4bd5ff-cgu.0.rcg /target/debug/build/getrandom-0f2ae90e99c5bb61/build_script_build-0f2ae90e99c5bb61.78giule9cmi5xz3xntrc0616a.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.794  collect2         471247 471205   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQBSNHt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.801  collect2         471246 471210   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cckx7VDU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.801  ld.lld           471250 471247   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQBSNHt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/getrandom-0f2ae90e99c5bb61/build_script_build-0f2ae90e99c5bb61 ...\n21.801  ld.lld           471251 471246   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cckx7VDU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60 ...\n21.805  rust-lld         471251 471246   0 \n21.810  build-script-bu  471188 469960   0 /target/debug/build/getrandom-0f2ae90e99c5bb61/build-script-build\n21.810  rustc            471248 469945   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cpp_demangle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n21.810  rust-lld         471250 471247   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQBSNHt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.818  collect2         471237 471236   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.824  cc               471249 471242   0 /usr/bin/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcpnC8lc/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.830  ld.lld           471255 471237   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc ...\n21.832  rust-lld         471255 471237   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.837  rustc            471243 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n21.839  collect2         471263 471249   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.843  rustc            471260 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n21.849  cc               471265 470166   0 /tmp/native-trace-469541-1783994548054/shims/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcBTOL4I/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.858  ld.lld           471273 471263   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc ...\n21.858  rustc            471262 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n21.859  rust-lld         471273 471263   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.873  cc               471274 471265   0 /usr/bin/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcBTOL4I/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.876  cc               471269 470483   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcOywn2F/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.878  cross            471288 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.880  rustc            471308 471288   0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.880  cc               471299 471269   0 /usr/bin/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcOywn2F/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.884  cc               471300 471037   0 /tmp/native-trace-469516-1783994548009/shims/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustctahcOs/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.889  rustc            471308 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.895  rustc            471270 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_sink --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n21.904  rustc            471277 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\")) -C metadata=f35517c6f15f2f68 ...\n21.904  cc               471333 471300   0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustctahcOs/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.906  rustc            471342 471288   0 /home/xmoe/.cargo/bin/rustc -vV\n21.914  rustc            471342 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.923  collect2         471341 471274   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.926  ld.lld           471357 471341   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378 ...\n21.930  rust-lld         471357 471341   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.931  cargo            471363 471288   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.941  cargo            471363 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.953  collect2         471394 471299   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWPcRyC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.958  rustc            471397 471363   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n"
}
```

#### Record 35

```json
{
  "argv": [
    "/target/debug/build/libc-8a22300c8f78b6db/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 466851,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
  "pid": 466851,
  "ppid": 466544,
  "root_cargo_pid": 466544,
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
  "build_script_root_pid": 466851,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 466853,
  "ppid": 466851,
  "root_cargo_pid": 466544,
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
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
  "pid": 467309,
  "ppid": 466544,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 38

```json
{
  "argv": [
    "/tmp/native-trace-465204-1783994526290/shims/git",
    "submodule",
    "update",
    "--init"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/tmp/native-trace-465204-1783994526290/shims/git",
  "pid": 467310,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/usr/bin/git",
  "pid": 467311,
  "ppid": 467310,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git-submodule",
  "event": "process_exec",
  "image": "/usr/lib/git-core/git-submodule",
  "pid": 467312,
  "ppid": 467311,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/usr/lib/git-core/git",
  "pid": 467316,
  "ppid": 467312,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "uname",
  "event": "process_exec",
  "image": "/usr/bin/uname",
  "pid": 467327,
  "ppid": 467312,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/usr/lib/git-core/git",
  "pid": 467328,
  "ppid": 467312,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 44

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-E",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/5311321163047493200detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467329,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 45

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/5311321163047493200detect_compiler_family.c",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467330,
  "ppid": 467329,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 46

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467331,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 47

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
    "-c",
    "brotli/common/dictionary.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467332,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 48

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/common/dictionary.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "dictionary.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467333,
  "ppid": 467332,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 49

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
    "/tmp/ccVa73fE.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467347,
  "ppid": 467332,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 50

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
    "-c",
    "brotli/dec/bit_reader.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467348,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 51

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/bit_reader.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "bit_reader.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467349,
  "ppid": 467348,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 52

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
    "/tmp/ccMWi1OQ.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467350,
  "ppid": 467348,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 53

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
    "-c",
    "brotli/dec/decode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467351,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 54

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/decode.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "decode.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467352,
  "ppid": 467351,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 55

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
    "/tmp/ccQKveE5.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467354,
  "ppid": 467351,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 56

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
    "-c",
    "brotli/dec/huffman.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467357,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 57

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/huffman.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "huffman.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467358,
  "ppid": 467357,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 58

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
    "/tmp/ccPKaJGz.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467361,
  "ppid": 467357,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 59

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
    "-c",
    "brotli/dec/state.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467363,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 60

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/state.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "state.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467364,
  "ppid": 467363,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 61

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
    "/tmp/cc4T4xQ1.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467368,
  "ppid": 467363,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 62

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
    "-c",
    "brotli/enc/backward_references.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467369,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 63

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/backward_references.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "backward_references.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467370,
  "ppid": 467369,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 64

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
    "/tmp/ccBKIHfr.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467380,
  "ppid": 467369,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 65

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
    "-c",
    "brotli/enc/backward_references_hq.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467382,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 66

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/backward_references_hq.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "backward_references_hq.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467383,
  "ppid": 467382,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 67

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
    "/tmp/ccJqjecr.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467395,
  "ppid": 467382,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 68

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
    "-c",
    "brotli/enc/bit_cost.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467397,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 69

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/bit_cost.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "bit_cost.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467399,
  "ppid": 467397,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 70

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
    "/tmp/cc9cq3lB.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467402,
  "ppid": 467397,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 71

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
    "-c",
    "brotli/enc/block_splitter.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467404,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 72

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/block_splitter.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "block_splitter.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467405,
  "ppid": 467404,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 73

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
    "/tmp/ccjIPcn7.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467424,
  "ppid": 467404,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 74

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
    "-c",
    "brotli/enc/brotli_bit_stream.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467427,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 75

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/brotli_bit_stream.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "brotli_bit_stream.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467428,
  "ppid": 467427,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 76

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/tmp/ccDRmlLO.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467435,
  "ppid": 467427,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 77

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
    "-c",
    "brotli/enc/cluster.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467439,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 78

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/cluster.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "cluster.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467440,
  "ppid": 467439,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 79

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
    "/tmp/ccYalp1H.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467444,
  "ppid": 467439,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 80

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
    "-c",
    "brotli/enc/compress_fragment.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467445,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 81

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/compress_fragment.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "compress_fragment.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467446,
  "ppid": 467445,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 82

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
    "/tmp/ccQBGv8d.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467453,
  "ppid": 467445,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 83

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "-c",
    "brotli/enc/compress_fragment_two_pass.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467454,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 84

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/compress_fragment_two_pass.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "compress_fragment_two_pass.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467455,
  "ppid": 467454,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 85

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/tmp/ccWkXESU.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467456,
  "ppid": 467454,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 86

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
    "-c",
    "brotli/enc/dictionary_hash.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467457,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 87

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/dictionary_hash.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "dictionary_hash.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467458,
  "ppid": 467457,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 88

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
    "/tmp/ccjKOVx6.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467460,
  "ppid": 467457,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 89

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
    "-c",
    "brotli/enc/encode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467461,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 90

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/encode.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "encode.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467462,
  "ppid": 467461,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 91

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
    "/tmp/ccD4wouo.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467465,
  "ppid": 467461,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 92

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
    "-c",
    "brotli/enc/entropy_encode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467467,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 93

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/entropy_encode.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "entropy_encode.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467468,
  "ppid": 467467,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 94

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
    "/tmp/ccUwGNES.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467469,
  "ppid": 467467,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 95

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
    "-c",
    "brotli/enc/histogram.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467470,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 96

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/histogram.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "histogram.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467471,
  "ppid": 467470,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 97

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
    "/tmp/ccdplC63.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467474,
  "ppid": 467470,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 98

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o",
    "-c",
    "brotli/enc/literal_cost.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467475,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 99

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/literal_cost.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "literal_cost.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467476,
  "ppid": 467475,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 100

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o",
    "/tmp/ccPiYVat.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467479,
  "ppid": 467475,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 101

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o",
    "-c",
    "brotli/enc/memory.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467481,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 102

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/memory.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "memory.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467482,
  "ppid": 467481,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 103

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o",
    "/tmp/ccccrRdU.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467483,
  "ppid": 467481,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 104

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o",
    "-c",
    "brotli/enc/metablock.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467484,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 105

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/metablock.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "metablock.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467485,
  "ppid": 467484,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 106

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o",
    "/tmp/ccFnMr38.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467486,
  "ppid": 467484,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 107

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o",
    "-c",
    "brotli/enc/static_dict.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467487,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 108

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/static_dict.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "static_dict.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467488,
  "ppid": 467487,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 109

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o",
    "/tmp/cc2XVbsl.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467492,
  "ppid": 467487,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 110

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o",
    "-c",
    "brotli/enc/utf8_util.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 467496,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 111

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/utf8_util.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "utf8_util.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 467497,
  "ppid": 467496,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 112

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o",
    "/tmp/cc5uSpe5.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 467501,
  "ppid": 467496,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 113

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 467502,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 114

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "sD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 467309,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 467503,
  "ppid": 467309,
  "root_cargo_pid": 466544,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 115

```json
{
  "crate": "brotli-sys",
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "bsrun:18f15322f5946163:dce7e71a45828fef:15703a84144f370f",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/build-script-build",
  "host": "x86_64-unknown-linux-gnu",
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "out_dir": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
  "success": true,
  "target": "powerpc64le-unknown-linux-gnu",
  "version": "0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "event_id": "bsrun:18f15322f5946163:325298fb080efefc:70bcf1a2ee0afd48",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
  "success": true,
  "target": null,
  "version": "0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
  "build_script_root_pid": 466851,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 466853,
  "ppid": 466851,
  "root_cargo_pid": 466544,
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
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/common/dictionary.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "dictionary.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/common/dictionary.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467333,
  "ppid": 467332,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 120

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/bit_reader.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "bit_reader.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/dec/bit_reader.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467349,
  "ppid": 467348,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 121

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/decode.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "decode.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/dec/decode.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467352,
  "ppid": 467351,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 122

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/huffman.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "huffman.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/dec/huffman.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467358,
  "ppid": 467357,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 123

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/dec/state.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "state.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/dec/state.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467364,
  "ppid": 467363,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 124

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/backward_references.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "backward_references.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/backward_references.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467370,
  "ppid": 467369,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 125

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/backward_references_hq.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "backward_references_hq.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/backward_references_hq.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467383,
  "ppid": 467382,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 126

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/bit_cost.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "bit_cost.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/bit_cost.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467399,
  "ppid": 467397,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 127

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/block_splitter.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "block_splitter.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/block_splitter.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467405,
  "ppid": 467404,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 128

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/brotli_bit_stream.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "brotli_bit_stream.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/brotli_bit_stream.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467428,
  "ppid": 467427,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 129

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/cluster.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "cluster.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/cluster.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467440,
  "ppid": 467439,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 130

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/compress_fragment.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "compress_fragment.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/compress_fragment.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467446,
  "ppid": 467445,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 131

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/compress_fragment_two_pass.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "compress_fragment_two_pass.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/compress_fragment_two_pass.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467455,
  "ppid": 467454,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 132

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/dictionary_hash.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "dictionary_hash.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/dictionary_hash.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467458,
  "ppid": 467457,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 133

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/encode.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "encode.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/encode.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467462,
  "ppid": 467461,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 134

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/entropy_encode.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "entropy_encode.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/entropy_encode.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467468,
  "ppid": 467467,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 135

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/histogram.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "histogram.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/histogram.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467471,
  "ppid": 467470,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 136

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/literal_cost.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "literal_cost.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/literal_cost.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467476,
  "ppid": 467475,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 137

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/memory.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "memory.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/memory.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467482,
  "ppid": 467481,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 138

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/metablock.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "metablock.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/metablock.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467485,
  "ppid": 467484,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 139

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/static_dict.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "static_dict.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/static_dict.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467488,
  "ppid": 467487,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 140

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "brotli/enc/utf8_util.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "utf8_util.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "..."
  ],
  "src": "brotli/enc/utf8_util.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 467497,
  "ppid": 467496,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 141

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
    "..."
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": true,
  "pid": 467502,
  "ppid": 467309,
  "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "root_cargo_pid": 466544,
  "build_script_root_pid": 467309,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:02:33.503489+00:00",
  "crate": "brotli-sys",
  "version": "0.3.2",
  "architecture": "ppc64le",
  "duration_seconds": 32.37098410911858,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "manifest_path": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "workspace_root": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
          "name": "brotli-sys",
          "version": "0.3.2",
          "manifest_path": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2"
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
      "pid": 466795,
      "ppid": 466586,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
      "event_id": "used:cc:f7a275179e4f3c0d:85334527128be1aa:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
      "pid": 466795,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
      "pid": 466795,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
      "pid": 466795,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
      "pid": 466795,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
      "pid": 466795,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
      "pid": 466795,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
      "context_path": "/tmp/native-trace-465204-1783994526290/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-465204-1783994526290/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 466795,
      "ppid": 466586,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/raw-dylibs",
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
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI",
        "/target/debug/build/libc-8a22300c8f78b6db",
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
          "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcanHyfI/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-466795-1783994531201141717.map",
      "pid": 466795,
      "ppid": 466586,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-466795-1783994531201141717.map"
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 467240,
      "ppid": 467199,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:7dcb2d8a395fa908:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
      "pid": 467240,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:3d3e98fbfacbd8c8:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "16a2c17da7dc95004490408657f8fc8243816ef6c99f809aeabc2d3b0e450be0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:69f2bc9c8244f2ed:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "28e7b5345900b77133ccbde03bb90a8c252fdd2b219ac6d30bce8481f0e40d17",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:399f8993f7acad1e:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "8b1948f692583a53faaa88cfa2c959be8e62dd848f0de0a62c5ca4307336746b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:a847d8b98a67505d:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "05311048b1d145f9b84b194bd49dcaa0be5f02eb709d9854f5c0c088502d0bfc",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:d29c4dece0ce2bd2:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "39a340bec4512c8ca2c8d3a4b1e841bbbad763009bf855f326057fd10d745537",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:7c2c3f75c52e67ee:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "587858f6817770d208be6f4191d9acb3904f4929feef568dc7fdc6ad57735d58",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:2bff78ba64bc3569:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "8bfa8688a1ef2c99e47a8176dcfcd6ca37d6ac7cfa47087cf2095c5ef97fb0c3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:d9b2673402ce23f5:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "a3028a0f117de5c5f124e24542cf1a688400e97adc9061c54f9f643d178c4df1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:a9918a0008e8e763:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "a59ce9021114960dad3b04ffaa0b17d40729b09be7b27a5d2fe84bffb69faccd",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:6e2578c54ab59c48:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "da117242e0b61f84c7e3be8c39c921ceb601b0e64670dddffb9f75eaec7f150f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:67df60076ef24811:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "3558f8f79dd4adca90cc9cabeb4edd6c2bdfc0d267b2387822e5989d0c99b679",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:9503a4e0d00d645f:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "bcc417cd39f195a546acad7ad52bd90ba2c30aec12a6c78a266ec9ccae840dc9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f4938bb327a0e643:c55467279ba7a335:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
      "pid": 467240,
      "sha256": "beef5da5a6c1990c62ffa6870030b80fca74e235a45ee672440764f3d7b85ad9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "context_path": "/tmp/native-trace-465204-1783994526290/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-465204-1783994526290/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 467240,
      "ppid": 467199,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
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
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustc2j2Apw/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1hvm1ad.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1hvm1ad.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-467240-1783994532687417057.map",
      "pid": 467240,
      "ppid": 467199,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-467240-1783994532687417057.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "exit_code": 128,
      "kind": "exec",
      "pid": 467310,
      "ppid": 467309,
      "success": false,
      "tool": "git",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "acq-ext:git:f4938bb327a0e643:e3b0c44298fc1c14",
      "exit_code": 128,
      "kind": "acquisition",
      "output": null,
      "pid": 467310,
      "success": false,
      "tool": "git",
      "url": null,
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "context_path": "/tmp/native-trace-465204-1783994526290/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "exit_code": 128,
      "host": "x86_64-unknown-linux-gnu",
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-465204-1783994526290/events/00000000-cargo-metadata.json",
      "num_jobs": "16",
      "opt_level": "0",
      "out_dir": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out",
      "pid": 467310,
      "ppid": 467309,
      "profile": "debug",
      "real_tool": "/usr/bin/git",
      "root_cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "success": false,
      "target": "powerpc64le-unknown-linux-gnu",
      "tool": "git",
      "workspace_root": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
      "parsed_event_count": 1054,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1055,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "u/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.460  cc               471033 470028   0 /tmp/native-trace-469308-1783994547847/shims/cc -m64 /target/debug/build/libc-08068d25dbed1dac/rustcp8SYR5/symbols.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n21.461  cc               471036 471033   0 /usr/bin/cc -m64 /target/debug/build/libc-08068d25dbed1dac/rustcp8SYR5/symbols.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n21.466  cc               471035 471031   0 /usr/bin/cc -m64 /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/rustckwrFQ6/symbols.o /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/build_script_build-3c1e0afe26da35f6.build_script_build.db007148713b585a /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/build_script_build-3c1e0afe26da35f6.73wwo9hmpn5ysmjykv0131bih.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.472  collect2         471040 471035   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZUAk0E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.473  ld.lld           471042 471040   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZUAk0E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/build_script_build-3c1e0afe26da35f6 ...\n21.474  rust-lld         471042 471040   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZUAk0E.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.475  rustup           471043 460320   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n21.481  build-script-bu  470997 469950   0 /target/debug/build/getrandom-0f2ae90e99c5bb61/build-script-build\n21.481  rustc            471037 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n21.482  build-script-bu  471032 469960   0 /target/debug/build/icu_properties_data-bb5269ffc4712489/build-script-build\n21.490  collect2         471048 471036   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgKSfEL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.494  ld.lld           471056 471048   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgKSfEL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac ...\n21.499  rust-lld         471056 471048   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgKSfEL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.518  build-script-bu  471061 469955   0 /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/build-script-build\n21.530  rustc            471084 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.539  rustc            471062 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\")) -C metadata=f35517c6f15f2f68 ...\n21.541  build-script-bu  471106 469917   0 /target/debug/build/cpp_demangle-bdc218a092b7c581/build-script-build\n21.552  rustc            471110 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n21.560  cc               471108 470040   0 /tmp/native-trace-469275-1783994547789/shims/cc -m64 /target/debug/build/cpp_demangle-bdc218a092b7c581/rustcrN9wN5/symbols.o /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n21.561  cc               471117 471108   0 /usr/bin/cc -m64 /target/debug/build/cpp_demangle-bdc218a092b7c581/rustcrN9wN5/symbols.o /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4. /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n21.566  rustc            471119 469917   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cpp_demangle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n21.571  collect2         471124 471117   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu62cNN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.576  ld.lld           471127 471124   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu62cNN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581 ...\n21.582  rustc            471128 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.583  rust-lld         471127 471124   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu62cNN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.595  rustc            471126 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.599  rustc            471038 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name percent_encoding --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/percent-encoding-2.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n21.605  build-script-bu  471080 469950   0 /target/debug/build/icu_properties_data-bb5269ffc4712489/build-script-build\n21.626  rustc            471102 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.639  rustc            471169 469945   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.647  build-script-bu  471173 469917   0 /target/debug/build/libc-08068d25dbed1dac/build-script-build\n21.652  rustc            471174 471173   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n21.656  rustc            471172 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_io --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n21.663  cc               471170 470381   0 /tmp/native-trace-469541-1783994548054/shims/cc -m64 /target/debug/build/getrandom-0f2ae90e99c5bb61/rustcXAbwQ5/symbols.o /target/debug/build/getrandom-0f2ae90e99c5bb61/build_script_build-0f2ae90e99c5bb61.build_script_build.cc6c5348da4bd5ff-cgu.0.rcg /target/debug/build/getrandom-0f2ae90e99c5bb61/build_script_build-0f2ae90e99c5bb61.78giule9cmi5xz3xntrc0616a.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.681  rustc            471145 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.681  rustc            471182 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_io --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n21.682  rustc            471184 469917   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.691  rustc            471179 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\")) -C metadata=f35517c6f15f2f68 ...\n21.694  build-script-bu  471190 469950   0 /target/debug/build/icu_normalizer_data-3c1e0afe26da35f6/build-script-build\n21.712  cc               471196 470379   0 /tmp/native-trace-469541-1783994548054/shims/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcZwovwi/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.718  rustc            471204 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_sink --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n21.727  cc               471210 471196   0 /usr/bin/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcZwovwi/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.745  cc               471233 470167   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcXdm63b/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.764  cc               471236 471233   0 /usr/bin/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcXdm63b/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.777  build-script-bu  471239 469945   0 /target/debug/build/cpp_demangle-bdc218a092b7c581/build-script-build\n21.783  cc               471242 470227   0 /tmp/native-trace-469516-1783994548009/shims/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcpnC8lc/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.785  rustc            471211 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer_data --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer_data-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(icu4x_custom_data) --check-cfg cfg(docsrs,test) --check-cfg ...\n21.791  cc               471205 471170   0 /usr/bin/cc -m64 /target/debug/build/getrandom-0f2ae90e99c5bb61/rustcXAbwQ5/symbols.o /target/debug/build/getrandom-0f2ae90e99c5bb61/build_script_build-0f2ae90e99c5bb61.build_script_build.cc6c5348da4bd5ff-cgu.0.rcg /target/debug/build/getrandom-0f2ae90e99c5bb61/build_script_build-0f2ae90e99c5bb61.78giule9cmi5xz3xntrc0616a.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.794  collect2         471247 471205   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQBSNHt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.801  collect2         471246 471210   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cckx7VDU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.801  ld.lld           471250 471247   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQBSNHt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/getrandom-0f2ae90e99c5bb61/build_script_build-0f2ae90e99c5bb61 ...\n21.801  ld.lld           471251 471246   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cckx7VDU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60 ...\n21.805  rust-lld         471251 471246   0 \n21.810  build-script-bu  471188 469960   0 /target/debug/build/getrandom-0f2ae90e99c5bb61/build-script-build\n21.810  rustc            471248 469945   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cpp_demangle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n21.810  rust-lld         471250 471247   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQBSNHt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.818  collect2         471237 471236   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.824  cc               471249 471242   0 /usr/bin/cc -m64 /target/debug/build/serde_core-60f8f7987f3ab3dc/rustcpnC8lc/symbols.o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.0.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.build_script_build.98100cc3e9cc1004-cgu.1.rc /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc.dp4p121bu3h4zwl79pxaopz7r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.830  ld.lld           471255 471237   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc ...\n21.832  rust-lld         471255 471237   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1DRccP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.837  rustc            471243 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n21.839  collect2         471263 471249   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.843  rustc            471260 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n21.849  cc               471265 470166   0 /tmp/native-trace-469541-1783994548054/shims/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcBTOL4I/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.858  ld.lld           471273 471263   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/serde_core-60f8f7987f3ab3dc/build_script_build-60f8f7987f3ab3dc ...\n21.858  rustc            471262 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28f523a37488b901 ...\n21.859  rust-lld         471273 471263   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHbLYZY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.873  cc               471274 471265   0 /usr/bin/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcBTOL4I/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.876  cc               471269 470483   0 /tmp/native-trace-469469-1783994547963/shims/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcOywn2F/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.878  cross            471288 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.880  rustc            471308 471288   0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.880  cc               471299 471269   0 /usr/bin/cc -m64 /target/debug/build/serde-064d128c4bf2ef60/rustcOywn2F/symbols.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.0.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.build_script_build.8dcc671ca241c9a1-cgu.1.rcgu.o /target/debug/build/serde-064d128c4bf2ef60/build_script_build-064d128c4bf2ef60.2qgpkx7ho0wu4zkdmgecd3jck.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.884  cc               471300 471037   0 /tmp/native-trace-469516-1783994548009/shims/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustctahcOs/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.889  rustc            471308 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.895  rustc            471270 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_sink --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n21.904  rustc            471277 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\")) -C metadata=f35517c6f15f2f68 ...\n21.904  cc               471333 471300   0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustctahcOs/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.906  rustc            471342 471288   0 /home/xmoe/.cargo/bin/rustc -vV\n21.914  rustc            471342 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.923  collect2         471341 471274   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.926  ld.lld           471357 471341   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378 ...\n21.930  rust-lld         471357 471341   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6v9QvK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.931  cargo            471363 471288   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.941  cargo            471363 471288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.953  collect2         471394 471299   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWPcRyC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.958  rustc            471397 471363   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-8a22300c8f78b6db/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 466851,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
      "pid": 466851,
      "ppid": 466544,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 466851,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 466853,
      "ppid": 466851,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
      "pid": 467309,
      "ppid": 466544,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/tmp/native-trace-465204-1783994526290/shims/git",
        "submodule",
        "update",
        "--init"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/tmp/native-trace-465204-1783994526290/shims/git",
      "pid": 467310,
      "ppid": 467309,
      "root_cargo_pid": 466544,
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
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/usr/bin/git",
      "pid": 467311,
      "ppid": 467310,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/git-core/git-submodule",
        "update",
        "--init"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git-submodule",
      "event": "process_exec",
      "image": "/usr/lib/git-core/git-submodule",
      "pid": 467312,
      "ppid": 467311,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/git-core/git",
        "--exec-path"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/usr/lib/git-core/git",
      "pid": 467316,
      "ppid": 467312,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/uname",
        "-s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "uname",
      "event": "process_exec",
      "image": "/usr/bin/uname",
      "pid": 467327,
      "ppid": 467312,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/git-core/git",
        "rev-parse",
        "--git-dir"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/usr/lib/git-core/git",
      "pid": 467328,
      "ppid": 467312,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-E",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/5311321163047493200detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467329,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/5311321163047493200detect_compiler_family.c",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467330,
      "ppid": 467329,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467331,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
        "-c",
        "brotli/common/dictionary.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467332,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/common/dictionary.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "dictionary.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467333,
      "ppid": 467332,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
        "/tmp/ccVa73fE.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467347,
      "ppid": 467332,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
        "-c",
        "brotli/dec/bit_reader.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467348,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/dec/bit_reader.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "bit_reader.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467349,
      "ppid": 467348,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
        "/tmp/ccMWi1OQ.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467350,
      "ppid": 467348,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
        "-c",
        "brotli/dec/decode.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467351,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/dec/decode.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "decode.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467352,
      "ppid": 467351,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
        "/tmp/ccQKveE5.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467354,
      "ppid": 467351,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
        "-c",
        "brotli/dec/huffman.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467357,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/dec/huffman.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "huffman.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467358,
      "ppid": 467357,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
        "/tmp/ccPKaJGz.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467361,
      "ppid": 467357,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
        "-c",
        "brotli/dec/state.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467363,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/dec/state.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "state.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467364,
      "ppid": 467363,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
        "/tmp/cc4T4xQ1.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467368,
      "ppid": 467363,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
        "-c",
        "brotli/enc/backward_references.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467369,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/backward_references.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "backward_references.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467370,
      "ppid": 467369,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
        "/tmp/ccBKIHfr.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467380,
      "ppid": 467369,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
        "-c",
        "brotli/enc/backward_references_hq.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467382,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/backward_references_hq.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "backward_references_hq.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467383,
      "ppid": 467382,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
        "/tmp/ccJqjecr.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467395,
      "ppid": 467382,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
        "-c",
        "brotli/enc/bit_cost.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467397,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/bit_cost.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "bit_cost.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467399,
      "ppid": 467397,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
        "/tmp/cc9cq3lB.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467402,
      "ppid": 467397,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
        "-c",
        "brotli/enc/block_splitter.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467404,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/block_splitter.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "block_splitter.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467405,
      "ppid": 467404,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
        "/tmp/ccjIPcn7.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467424,
      "ppid": 467404,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
        "-c",
        "brotli/enc/brotli_bit_stream.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467427,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/brotli_bit_stream.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "brotli_bit_stream.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467428,
      "ppid": 467427,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
        "/tmp/ccDRmlLO.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467435,
      "ppid": 467427,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
        "-c",
        "brotli/enc/cluster.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467439,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/cluster.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "cluster.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467440,
      "ppid": 467439,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
        "/tmp/ccYalp1H.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467444,
      "ppid": 467439,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
        "-c",
        "brotli/enc/compress_fragment.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467445,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/compress_fragment.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "compress_fragment.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467446,
      "ppid": 467445,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
        "/tmp/ccQBGv8d.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467453,
      "ppid": 467445,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
        "-c",
        "brotli/enc/compress_fragment_two_pass.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467454,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/compress_fragment_two_pass.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "compress_fragment_two_pass.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467455,
      "ppid": 467454,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
        "/tmp/ccWkXESU.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467456,
      "ppid": 467454,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
        "-c",
        "brotli/enc/dictionary_hash.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467457,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/dictionary_hash.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "dictionary_hash.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467458,
      "ppid": 467457,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
        "/tmp/ccjKOVx6.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467460,
      "ppid": 467457,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
        "-c",
        "brotli/enc/encode.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467461,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/encode.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "encode.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467462,
      "ppid": 467461,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
        "/tmp/ccD4wouo.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467465,
      "ppid": 467461,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
        "-c",
        "brotli/enc/entropy_encode.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467467,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/entropy_encode.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "entropy_encode.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467468,
      "ppid": 467467,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
        "/tmp/ccUwGNES.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467469,
      "ppid": 467467,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
        "-c",
        "brotli/enc/histogram.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467470,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/histogram.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "histogram.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467471,
      "ppid": 467470,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
        "/tmp/ccdplC63.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467474,
      "ppid": 467470,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o",
        "-c",
        "brotli/enc/literal_cost.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467475,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/literal_cost.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "literal_cost.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467476,
      "ppid": 467475,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o",
        "/tmp/ccPiYVat.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467479,
      "ppid": 467475,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o",
        "-c",
        "brotli/enc/memory.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467481,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/memory.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "memory.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467482,
      "ppid": 467481,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o",
        "/tmp/ccccrRdU.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467483,
      "ppid": 467481,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o",
        "-c",
        "brotli/enc/metablock.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467484,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/metablock.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "metablock.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467485,
      "ppid": 467484,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o",
        "/tmp/ccFnMr38.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467486,
      "ppid": 467484,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o",
        "-c",
        "brotli/enc/static_dict.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467487,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/static_dict.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "static_dict.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467488,
      "ppid": 467487,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o",
        "/tmp/cc2XVbsl.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467492,
      "ppid": 467487,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o",
        "-c",
        "brotli/enc/utf8_util.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 467496,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "brotli/enc/utf8_util.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "utf8_util.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 467497,
      "ppid": 467496,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o",
        "/tmp/cc5uSpe5.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 467501,
      "ppid": 467496,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "cqD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 467502,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "sD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 467309,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 467503,
      "ppid": 467309,
      "root_cargo_pid": 466544,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "brotli-sys",
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "bsrun:18f15322f5946163:dce7e71a45828fef:15703a84144f370f",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/build-script-build",
      "host": "x86_64-unknown-linux-gnu",
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "out_dir": "/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
      "success": true,
      "target": "powerpc64le-unknown-linux-gnu",
      "version": "0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
      "cwd": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "event_id": "bsrun:18f15322f5946163:325298fb080efefc:70bcf1a2ee0afd48",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
      "out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
      "success": true,
      "target": null,
      "version": "0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2",
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
      "build_script_root_pid": 466851,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 466853,
      "ppid": 466851,
      "root_cargo_pid": 466544,
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
