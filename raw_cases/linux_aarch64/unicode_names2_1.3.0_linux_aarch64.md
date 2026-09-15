# `unicode_names2` `1.3.0`

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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib"
  ],
  "libs": [
    "c",
    "m",
    "rt",
    "pthread",
    "gcc_s",
    "util",
    "rt",
    "pthread",
    "m",
    "dl",
    "c"
  ],
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI",
    "/target/debug/build/unicode_names2-b44907ea69b5d510",
    "/target/debug/deps",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps"
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
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib(phf_codegen-2be8357290ad31b2.phf_codegen.781f7385c25482d5-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib(phf_shared-463e99589cec8ca1.phf_shared.facf40192815ae9c-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib(siphasher-3d4a2c80230e081b.siphasher.504cc0aff0ef069a-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib(rand-fccf93ef6a6b0ceb.rand.d99ab2b3875cfe03-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib(rand-fccf93ef6a6b0ceb.rand.d99ab2b3875cfe03-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib(rand_chacha-4d6cf44e1aa1ed9a.rand_chacha.c8af3e8aa4620bed-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib(rand_chacha-4d6cf44e1aa1ed9a.rand_chacha.c8af3e8aa4620bed-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/librand_core-ea21890b3025e524.rlib(rand_core-ea21890b3025e524.rand_core.82143084d8d323ec-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib(getrandom-9f9f6891c3ecf55f.getrandom.70e14cb97acd3eb6-cgu.0.rcgu.o",
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
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib(std_detect-e305c7135f50bfab.std_detect.4859ea97f15b1179-cgu.0.rcgu.o",
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
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so",
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
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-687077-1783995524155934565.map",
  "pid": 687077,
  "ppid": 686979,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-687077-1783995524155934565.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "workspace_root": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.2",
      "name": "aho-corasick",
      "version": "1.1.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getopts@0.2.21",
      "name": "getopts",
      "version": "0.2.21",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.12",
      "name": "getrandom",
      "version": "0.2.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
      "name": "libc",
      "version": "0.2.153",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.21",
      "name": "log",
      "version": "0.4.21",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.1",
      "name": "memchr",
      "version": "2.7.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf@0.11.2",
      "name": "phf",
      "version": "0.11.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.11.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.11.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_codegen@0.11.2",
      "name": "phf_codegen",
      "version": "0.11.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.11.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.11.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_generator@0.11.2",
      "name": "phf_generator",
      "version": "0.11.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_shared@0.11.2",
      "name": "phf_shared",
      "version": "0.11.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.17",
      "name": "ppv-lite86",
      "version": "0.2.17",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.78",
      "name": "proc-macro2",
      "version": "1.0.78",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.35",
      "name": "quote",
      "version": "1.0.35",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.8.5",
      "name": "rand",
      "version": "0.8.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.3.1",
      "name": "rand_chacha",
      "version": "0.3.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.6.4",
      "name": "rand_core",
      "version": "0.6.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_xorshift@0.3.0",
      "name": "rand_xorshift",
      "version": "0.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.10.3",
      "name": "regex",
      "version": "1.10.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.6",
      "name": "regex-automata",
      "version": "0.4.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.2",
      "name": "regex-syntax",
      "version": "0.8.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#siphasher@0.3.11",
      "name": "siphasher",
      "version": "0.3.11",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.52",
      "name": "syn",
      "version": "2.0.52",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.52/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.52"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
      "name": "unicode-ident",
      "version": "1.0.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.11",
      "name": "unicode-width",
      "version": "0.1.11",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.11/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode_names2@1.2.2",
      "name": "unicode_names2",
      "version": "1.2.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2-1.2.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2-1.2.2"
    },
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
      "name": "unicode_names2",
      "version": "1.3.0",
      "manifest_path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode_names2_generator@1.3.0",
      "name": "unicode_names2_generator",
      "version": "1.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_generator-1.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_generator-1.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode_names2_macros@1.1.0",
      "name": "unicode_names2_macros",
      "version": "1.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_macros-1.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_macros-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
      "name": "wasi",
      "version": "0.11.0+wasi-snapshot-preview1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1"
    }
  ],
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "exit_code": 0,
  "kind": "exec",
  "pid": 684673,
  "ppid": 684501,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "used:cc:b47364ada97c6bc2:fd55da75181da1ab:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
  "pid": 684673,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "used:cc:b47364ada97c6bc2:8fbc204c2de40ae3:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
  "pid": 684673,
  "sha256": "1c1bda37289ec1d821d844082238c8264f2503ddb9285e4c4b35874be718b5b0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "used:cc:b47364ada97c6bc2:8fa1e6b2f28555cd:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
  "pid": 684673,
  "sha256": "5e70191dfb043a5385388b604c5c1feba8fec2b44fdb25873028a427923b8d6a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "used:cc:b47364ada97c6bc2:56ea4f27c87e1fc7:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
  "pid": 684673,
  "sha256": "8197d6a77e8ee592aad69945794d29560ea22f5d99de7fd4a19d8a5ec3c53dd4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "used:cc:b47364ada97c6bc2:6ef887c52156788c:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
  "pid": 684673,
  "sha256": "9f762bbe468a79bebb41c2e60a430efa1e822b7c5745db8269c41350de4cf6f5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
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
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "context_path": "/tmp/native-trace-682693-1783995461657/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-682693-1783995461657/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 684673,
  "ppid": 684501,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp",
    "/target/debug/build/libc-c3c858474dcfa7e6",
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
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-684673-1783995495564756249.map",
  "pid": 684673,
  "ppid": 684501,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-684673-1783995495564756249.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 687077,
  "ppid": 686979,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:a587e75d6d2d30d5:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
  "pid": 687077,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:44aa42a7477a73bf:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "f189463a19503b07293b02eab57bb6a268f722caa1b0fd3bf01819c9e778f96d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:8f581b81fcd1f91d:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "d54965163573b5b6a94bb207e1853ac756c7a6eb0b38a21ada84883adab78a46",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:c020ac05dcd7655a:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "97e49859a3d32ffd27252e0e8539706bc58649b32069e416cbb77967580b65d4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:429a61bb26f8cf41:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "5dc6abe6c5223e7220956797a7a42a04916d6823f5e56ca34d385268f2514eab",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:f4784c2c7bc2094d:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "ae45d2c1fdb5e4bf4b5ab83c5dbbb20cf9793e6066b82b2adf67788724c4bf84",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:52be11ddf2214a50:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "d89ccb939e1883d4dffd86119bb21bf5d1709587ca435e421c9954cf66919888",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:1b02c3e1cda26131:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "c9166dd74f490b2ccd253b27bc29f6a0f1a3ed8bf45783589a74790ff0314599",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:0fd9d30e95dd9fe6:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "2ae6d36184fa6a41b32c3a8fb43aa2c2291e8e5663ef28fe79fe8748969ec580",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:5ff76df10d50778e:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "776d19a30e8b40884c1af49a2c34a554513cd317716009c5d829ee34d62195d0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:d7573de98153f71f:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "af6b4449e342959df2e506900148e1c2d070c2d493aa4b78200da74d5a3828d6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:bb8f99c81bf2ebed:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "a6d24a25a99213780f2ff094d1596912f308236c1f72ff1b2ae35b45e7b9352e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "used:cc:4206ecad076f83f2:4e73252e999d8849:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
  "pid": 687077,
  "sha256": "2ba624871577aaea609c57281a8c0c175c6a5df41b33f4e3b1da3b23bde7d746",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib"
  ],
  "libs": [
    "c",
    "m",
    "rt",
    "pthread",
    "gcc_s",
    "util",
    "rt",
    "pthread",
    "m",
    "dl",
    "c"
  ],
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "context_path": "/tmp/native-trace-682693-1783995461657/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-682693-1783995461657/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 687077,
  "ppid": 686979,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
    "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
    "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
    "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
    "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
    "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
    "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
    "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
    "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
    "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
    "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
    "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lc",
    "-lm",
    "-lrt",
    "-lpthread",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI",
    "/target/debug/build/unicode_names2-b44907ea69b5d510",
    "/target/debug/deps",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
    "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps"
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
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib(phf_codegen-2be8357290ad31b2.phf_codegen.781f7385c25482d5-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib(phf_shared-463e99589cec8ca1.phf_shared.facf40192815ae9c-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib(siphasher-3d4a2c80230e081b.siphasher.504cc0aff0ef069a-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib(rand-fccf93ef6a6b0ceb.rand.d99ab2b3875cfe03-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib(rand-fccf93ef6a6b0ceb.rand.d99ab2b3875cfe03-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib(rand_chacha-4d6cf44e1aa1ed9a.rand_chacha.c8af3e8aa4620bed-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib(rand_chacha-4d6cf44e1aa1ed9a.rand_chacha.c8af3e8aa4620bed-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/librand_core-ea21890b3025e524.rlib(rand_core-ea21890b3025e524.rand_core.82143084d8d323ec-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib(getrandom-9f9f6891c3ecf55f.getrandom.70e14cb97acd3eb6-cgu.0.rcgu.o",
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
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib(std_detect-e305c7135f50bfab.std_detect.4859ea97f15b1179-cgu.0.rcgu.o",
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
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so",
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
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-687077-1783995524155934565.map",
  "pid": 687077,
  "ppid": 686979,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-687077-1783995524155934565.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 28

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

#### Record 29

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 853,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 855,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "54d47e50.prost_derive.a5e8fd9e3a8526b6-cgu.14.rcgu.o ...\n59.527  collect2         688362 688361   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGza5Uu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libprost_derive-d5b7106554d47e50.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcPigg2I/raw-dylibs ...\n59.622  ld.lld           688364 688362   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGza5Uu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprost_derive-d5b7106554d47e50.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcPigg2I/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n59.623  rust-lld         688364 688362   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGza5Uu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprost_derive-d5b7106554d47e50.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n60.093  sh               688373 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n60.219  rustc            688377 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cranelift_codegen --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-codegen-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"gimli\" --cfg feature=\"std\" ...\n60.219  rustc            688374 672464   0 \n60.219  cpuUsage.sh      688373 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n60.323  sed              688378 688373   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n60.439  cat              688382 688373   0 /usr/bin/cat /proc/2240539/stat\n60.441  cat              688386 688373   0 /usr/bin/cat /proc/4193716/stat\n60.443  sleep            688387 688373   0 /usr/bin/sleep 1\n60.775  16               688411 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n60.936  frpc             688411 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n61.484  sed              688425 688373   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n61.485  rustc            688424 671759   0 /sbin/rustc --crate-name cranelift_entity --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-entity-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"enable-serde\" --cfg feature=\"serde\" --check-cfg cfg(docsrs,test) ...\n61.577  cat              688431 688373   0 /usr/bin/cat /proc/2240539/stat\n61.577  cat              688433 688373   0 /usr/bin/cat /proc/4193716/stat\n61.617  rustc            688430 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name indexmap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-1.9.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"serde\" --cfg feature=\"serde-1\" --cfg feature=\"std\" ...\n61.725  rustc            688438 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.5.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"indexmap\", \"preserve_order\")) ...\n61.780  rustc            688437 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bincode --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"i128\")) -C metadata=78ed03366453242f ...\n61.967  rustc            688450 684688   0 /usr/local/sbin/rustc --crate-name ureq --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ureq-3.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"_rustls\" --cfg feature=\"_tls\" --cfg feature=\"rustls-no-provider\" ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ureq --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ureq-3.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"_rustls\" --cfg feature=\"_tls\" --cfg feature=\"rustls-no-provider\" ...\n62.018  as               688454 683870   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n62.267  rustc            688461 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prost --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prost-0.14.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"std\" ...\n62.565  riscv64-linux-g  688472 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n62.577  cc1plus          688473 688472   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n62.816  riscv64-linux-g  688482 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n62.816  cc1plus          688483 688482   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n62.817  rustc            688478 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tracing_attributes --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tracing-attributes-0.1.29/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(flaky_tests) --check-cfg ...\n62.817  rustc            688476 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-macros-2.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n62.817  rustc            688481 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name async_trait --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-trait-0.1.88/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n62.822  rustc            688488 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prost_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prost-derive-0.14.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n62.824  rustc            688489 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pin_project_internal --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-internal-1.1.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=clippy::unused_trait_names --warn=unreachable_pub --warn=unnameable_types --warn=unexpected_cfgs ...\n63.142  cargo            688502 686425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n63.208  rustc            688506 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n63.363  as               688516 686257   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-StackIR.o /tmp/ccU0JTjH.s\n63.560  rustc            688522 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n64.232  rustc            688536 671759   0 \n64.295  rustc            688535 672464   0 \n64.347  sh               688537 2147557   0 /bin/sh -c which ps\n64.456  which            688537 2147557   0 /usr/bin/which ps\n64.630  ps               688546 2147557   0 \n64.630  rustc            688541 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prost_types --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prost-types-0.14.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(kani) --cfg feature=\"default\" --cfg ...\n64.630  rustc            688547 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_jit_debug --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-jit-debug-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"gdb_jit_int\" --cfg feature=\"object\" --cfg feature=\"once_cell\" ...\n64.630  sh               688546 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n64.971  rustc            688564 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ppv_lite86 --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"simd\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n64.971  rustc            688561 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=fe406ea3c765137d ...\n64.992  rustc            688563 688502   0 \n65.085  rustc            688572 688502   0 /usr/bin/rustc --crate-name siphasher --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ... /usr/local/sbin/rustc --crate-name siphasher --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n65.088  rustc            688579 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name log --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_s -C metadata=f26460ac6816b597 ...\n65.197  rustc            688583 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name siphasher --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n65.356  cpuUsage.sh      688590 2147557   0 \n65.356  rustc            688587 688502   0 /bin/rustc --crate-name unicode_width --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bench\", \"compiler_builtins\", \"core\", \"default\", \"no_std\", \"rustc-dep-of-std\", \"std\")) ...\n65.356  sed              688598 688590   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n65.356  sh               688590 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n65.482  cat              688603 688590   0 /usr/bin/cat /proc/2240539/stat\n65.554  cat              688606 688590   0 /usr/bin/cat /proc/4193716/stat\n65.554  sleep            688607 688590   0 /usr/bin/sleep 1\n66.558  sed              688618 688590   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n66.788  rustc            688623 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getopts --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\", \"std\")) -C metadata=9a30f0b23db5a9c1 ...\n66.842  cat              688629 688590   0 /usr/bin/cat /proc/2240539/stat\n66.941  cat              688634 688590   0 /usr/bin/cat /proc/4193716/stat\n66.961  as               688636 687343   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/bd3f41d09f19c9b0-ExtractFunction.o /tmp/cc3WIh5R.s\n67.060  rustc            688650 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n67.103  rustc            688652 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n67.690  rustc            688677 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name gimli --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gimli-0.27.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"fallible-iterator\" --cfg feature=\"indexmap\" --cfg feature=\"read\" ...\n67.702  rustc            688678 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name object --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/object-0.30.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"coff\" --cfg feature=\"crc32fast\" --cfg feature=\"elf\" ...\n67.702  rustc            688681 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_shared --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n67.847  rustc            688692 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_shared --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n68.293  powerpc64le-lin  688704 629465   0 /usr/local/sbin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n68.489  as               688710 687136   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/bd3f41d09f19c9b0-FuncCastEmulation.o /tmp/cc9KZHbc.s\n68.708  cc1plus          688705 688704   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/Poppify.cpp ...\n68.940  cc               688708 688561   0 /tmp/native-trace-686425-1783995514820/shims/cc -m64 /target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n69.193  cc               688726 688708   0 /usr/bin/cc -m64 /target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n69.241  collect2         688732 688726   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccR0bHXw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n69.287  ld.lld           688734 688732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccR0bHXw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6 ...\n69.314  rust-lld         688734 688732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccR0bHXw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n69.345  sh               688738 2147557   0 /bin/sh -c which ps\n69.348  which            688738 2147557   0 /usr/bin/which ps\n69.352  sh               688739 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n69.354  ps               688739 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n69.446  rustc            688744 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.11.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"macros\", \"phf_macros\", \"serde\", \"std\", \"uncased\", \"unicase\")) -C metadata=244ba6dc0c36fded ...\n69.492  aarch64-linux-g  688750 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n69.495  cc1plus          688751 688750   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n69.618  cc               688765 688476   0 /tmp/native-trace-682662-1783995461197/shims/cc -Wl,--version-script=/target/debug/deps/rustc754i4h/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc754i4h/symbols.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.0.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.1.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.2.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.3.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.4.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.5.rcgu.o /target/debug/deps/rustc754i4h/rmeta.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.59le7k6awoiay7kpeps9nx9hx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 ...\n69.804  cc               688772 688765   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc754i4h/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc754i4h/symbols.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.0.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.1.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.2.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.3.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.4.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.5.rcgu.o /target/debug/deps/rustc754i4h/rmeta.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.59le7k6awoiay7kpeps9nx9hx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 ...\n69.998  as               688784 629915   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/e951192f0fd9e7b0-cfg.o /tmp/ccqRxHUo.s\n70.017  build-script-bu  688783 688502   0 /target/debug/build/libc-c3c858474dcfa7e6/build-script-build\n70.032  rustc            688786 688783   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n70.069  rustc            688781 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_cache --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-cache-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=f903cf7d75a35212 ...\n70.089  rustc            688793 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=50306f6091620542 ...\n70.134  sh               688796 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n70.136  cpuUsage.sh      688796 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n70.138  sed              688797 688796   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n70.143  cat              688801 688796   0 /usr/bin/cat /proc/2240539/stat\n70.145  cat              688803 688796   0 /usr/bin/cat /proc/4193716/stat\n70.147  sleep            688804 688796   0 \n70.155  rustc            688802 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_environ --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-environ-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"component-model\")) -C metadata=461fac09b7d0875b ...\n70.259  rust-lld         688815 688812   0 \n70.259  collect2         688812 688772   0 \n70.259  ld.lld           688815 688812   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIGbcMT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libtokio_macros-7c36a25fc8e4e5b1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc754i4h/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n70.431  riscv64-linux-g  688808 629151   0 \n70.434  cc1plus          688824 688808   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n70.992  cc               688833 688481   0 /tmp/native-trace-682662-1783995461197/shims/cc -Wl,--version-script=/target/debug/deps/rustcLIs5qr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcLIs5qr/symbols.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.0.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.1.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.2.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.3.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.4.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.5.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.6.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.7.rcgu.o /target/debug/deps/rustcLIs5qr/rmeta.o /target/debug/deps/async_trait-761c3ce8bad53e9b.a6fsmfpscohxzxyo0qix8qvvt.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib ...\n71.090  cc               688837 688833   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcLIs5qr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcLIs5qr/symbols.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.0.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.1.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.2.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.3.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.4.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.5.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.6.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.7.rcgu.o /target/debug/deps/rustcLIs5qr/rmeta.o /target/debug/deps/async_trait-761c3ce8bad53e9b.a6fsmfpscohxzxyo0qix8qvvt.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib ...\n71.148  sed              688841 688796   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n71.150  cat              688842 688796   0 /usr/bin/cat /proc/2240539/stat\n71.153  cat              688844 688796   0 /usr/bin/cat /proc/4193716/stat\n71.175  runc             688836 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process13703616 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n71.199  exe              688855 688836   0 /proc/self/exe init\n71.240  collect2         688838 688837   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaReYaN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libasync_trait-761c3ce8bad53e9b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcLIs5qr/raw-dylibs ...\n71.246  ld.lld           688865 688838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaReYaN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libasync_trait-761c3ce8bad53e9b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcLIs5qr/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n71.250  curl             688857 688836   0 /usr/bin/curl -f http://localhost:9091/healthz\n71.253  rust-lld         688865 688838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaReYaN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libasync_trait-761c3ce8bad53e9b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n72.299  runc             688917 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1642994706 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n72.319  exe              688927 688917   0 /proc/self/exe init\n72.384  etcdctl          688930 688917   0 /usr/local/bin/etcdctl endpoint health\n72.455  aarch64-linux-g  688944 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n72.463  cc1plus          688948 688944   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/Poppify.cpp ...\n73.994  rustc            688975 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getrandom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"rdrand\", \"rustc-dep-of-std\", \"std\", \"test-in-browser ...\n74.191  as               688986 687455   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/bd3f41d09f19c9b0-FuncCastEmulation.o /tmp/cchmEdYk.s\n74.262  rustc            688990 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-1.47.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(fuzzing) --check-cfg cfg(loom) --check-cfg ...\n74.300  cc               688998 688489   0 /tmp/native-trace-682662-1783995461197/shims/cc -Wl,--version-script=/target/debug/deps/rustczulj8m/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustczulj8m/symbols.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.00.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.01.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.02.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.03.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.04.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.05.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.06.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.07.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.08.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.09.rcgu.o /target/debug/deps/rustczulj8m/rmeta.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.9ub9rsopcxv7h1d1xxpdu76pj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib ...\n74.302  cc               688999 688998   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustczulj8m/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustczulj8m/symbols.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.00.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.01.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.02.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.03.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.04.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.05.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.06.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.07.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.08.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.09.rcgu.o /target/debug/deps/rustczulj8m/rmeta.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.9ub9rsopcxv7h1d1xxpdu76pj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib ...\n74.306  collect2         689000 688999   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJOnYu6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libpin_project_internal-7c0fe5df944f1a10.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustczulj8m/raw-dylibs ...\n74.309  ld.lld           689001 689000   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJOnYu6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpin_project_internal-7c0fe5df944f1a10.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustczulj8m/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n74.313  rust-lld         689001 689000   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJOnYu6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpin_project_internal-7c0fe5df944f1a10.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n74.342  sh               689004 2147557   0 /bin/sh -c which ps\n74.344  which            689004 2147557   0 /usr/bin/which ps\n74.350  sh               689006 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n74.351  ps               689006 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n74.473  sh               689023 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n74.476  cpuUsage.sh      689023 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n74.480  sed              689024 689023   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n74.485  cat              689025 689023   0 /usr/bin/cat /proc/2240539/stat\n74.489  cat              689026 689023   0 /usr/bin/cat /proc/4193716/stat\n74.491  sleep            689027 689023   0 /usr/bin/sleep 1\n74.685  rustc            689032 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"getrandom\" --cfg feature=\"std\" ...\n74.884  cc               689038 688478   0 /tmp/native-trace-682662-1783995461197/shims/cc -Wl,--version-script=/target/debug/deps/rustcCoVT2C/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCoVT2C/symbols.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.00.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.01.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.02.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.03.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.04.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.05.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.06.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.07.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.08.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.09.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.10.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.11.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.12.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.13.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.14.rcgu.o ...\n74.887  cc               689039 689038   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcCoVT2C/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCoVT2C/symbols.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.00.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.01.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.02.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.03.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.04.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.05.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.06.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.07.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.08.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.09.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.10.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.11.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.12.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.13.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.14.rcgu.o ...\n74.985  collect2         689045 689039   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwOfG76.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libtracing_attributes-7c7c9daeed01a338.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcCoVT2C/raw-dylibs ...\n74.990  ld.lld           689046 689045   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwOfG76.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libtracing_attributes-7c7c9daeed01a338.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcCoVT2C/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n74.999  rust-lld         689046 689045   0 \n75.071  rustc            689047 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio_util --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-util-0.7.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(fuzzing) --check-cfg cfg(loom) --check-cfg ...\n75.076  rustc            689048 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio_stream --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-stream-0.1.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"net\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"fs\", \"full\", \"io-util\", \"net\", \"signal\", \"sync\", \"time\", \"tokio-util\")) ...\n75.379  rustc            689079 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pin_project --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-1.1.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::unused_trait_names --warn=unreachable_pub --warn=unnameable_types --warn=unexpected_cfgs --warn=clippy::undocumented_unsafe_blocks --warn=clippy::transmute_undefined_repr ...\n75.512  cat              689085 689023   0 /usr/bin/cat /proc/4193716/stat\n75.515  as               689081 642532   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/f7deeeb1a9f9c241-module-utils.o /tmp/cctt4Sqr.s\n75.515  sed              689082 689023   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n75.515  cat              689083 689023   0 /usr/bin/cat /proc/2240539/stat\n"
}
```

#### Record 30

```json
{
  "argv": [
    "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 684725,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
  "pid": 684725,
  "ppid": 684443,
  "root_cargo_pid": 684443,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "_build_script_out_dir": "/target/debug/build/libc-c3c858474dcfa7e6/out"
}
```

#### Record 31

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 684725,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 684729,
  "ppid": 684725,
  "root_cargo_pid": 684443,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "_build_script_out_dir": "/target/debug/build/libc-c3c858474dcfa7e6/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 32

```json
{
  "argv": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 687139,
  "build_script_target_dir": "unicode_names2-b44907ea69b5d510",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
  "pid": 687139,
  "ppid": 684443,
  "root_cargo_pid": 684443,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "_build_script_out_dir": "/target/debug/build/unicode_names2-b44907ea69b5d510/out"
}
```

#### Record 33

```json
{
  "crate": "libc",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "bsrun:2b971722f0fa3d65:9d24ac71553b3fba:82a359e119a38779",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "out_dir": "/target/debug/build/libc-c3c858474dcfa7e6/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
  "success": true,
  "target": null,
  "version": "0.2.153",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cwd_prefix"
  }
}
```

#### Record 34

```json
{
  "crate": "unicode_names2",
  "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "event_id": "bsrun:8946c8a61c9bb131:1a37a2067149b32e:a43ba5a7be190f37",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
  "out_dir": "/target/debug/build/unicode_names2-b44907ea69b5d510/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
  "success": true,
  "target": null,
  "version": "1.3.0",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 35

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 684725,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 684729,
  "ppid": 684725,
  "root_cargo_pid": 684443,
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
  "time": "2026-07-14T02:19:28.256344+00:00",
  "crate": "unicode_names2",
  "version": "1.3.0",
  "architecture": "aarch64",
  "duration_seconds": 119.22825205186382,
  "trace_record_count": 34,
  "trace_owner_summary": {
    "owner_package_count": 30,
    "owner_packages": [
      {
        "crate": "wasi",
        "version": "0.11.0+wasi-snapshot-preview1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1/Cargo.toml"
      },
      {
        "crate": "unicode_names2_generator",
        "version": "1.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode_names2_generator@1.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_generator-1.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_generator-1.3.0/Cargo.toml"
      },
      {
        "crate": "unicode_names2_macros",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode_names2_macros@1.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_macros-1.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_macros-1.1.0/Cargo.toml"
      },
      {
        "crate": "phf_generator",
        "version": "0.11.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_generator@0.11.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.2/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml"
      },
      {
        "crate": "unicode-width",
        "version": "0.1.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.11/Cargo.toml"
      },
      {
        "crate": "unicode_names2",
        "version": "1.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode_names2@1.2.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2-1.2.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2-1.2.2/Cargo.toml"
      },
      {
        "crate": "rand_xorshift",
        "version": "0.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_xorshift@0.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.3.0/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.2/Cargo.toml"
      },
      {
        "crate": "phf_codegen",
        "version": "0.11.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_codegen@0.11.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.11.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.11.2/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.78",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.78",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.8.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.2/Cargo.toml"
      },
      {
        "crate": "phf_shared",
        "version": "0.11.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_shared@0.11.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.2/Cargo.toml"
      },
      {
        "crate": "ppv-lite86",
        "version": "0.2.17",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.17",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17/Cargo.toml"
      },
      {
        "crate": "rand_chacha",
        "version": "0.3.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.3.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/Cargo.toml"
      },
      {
        "crate": "getrandom",
        "version": "0.2.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.12/Cargo.toml"
      },
      {
        "crate": "siphasher",
        "version": "0.3.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#siphasher@0.3.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11/Cargo.toml"
      },
      {
        "crate": "rand_core",
        "version": "0.6.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.6.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/Cargo.toml"
      },
      {
        "crate": "getopts",
        "version": "0.2.21",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getopts@0.2.21",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/Cargo.toml"
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
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.7.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.1/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.35",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.35",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.10.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.10.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.3/Cargo.toml"
      },
      {
        "crate": "log",
        "version": "0.4.21",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.21",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21/Cargo.toml"
      },
      {
        "crate": "phf",
        "version": "0.11.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf@0.11.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.11.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.11.2/Cargo.toml"
      },
      {
        "crate": "rand",
        "version": "0.8.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.8.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.52",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.52",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.52",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.52/Cargo.toml"
      },
      {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "manifest_path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 29,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "unicode_names2",
        "version": "1.3.0",
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
        "crate": "libc",
        "version": "0.2.153",
        "event_count": 10,
        "kind_counts": {
          "exec": 1,
          "used_input": 5,
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
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "workspace_root": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.2",
          "name": "aho-corasick",
          "version": "1.1.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getopts@0.2.21",
          "name": "getopts",
          "version": "0.2.21",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.12",
          "name": "getrandom",
          "version": "0.2.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
          "name": "libc",
          "version": "0.2.153",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.21",
          "name": "log",
          "version": "0.4.21",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.1",
          "name": "memchr",
          "version": "2.7.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf@0.11.2",
          "name": "phf",
          "version": "0.11.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.11.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.11.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_codegen@0.11.2",
          "name": "phf_codegen",
          "version": "0.11.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.11.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.11.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_generator@0.11.2",
          "name": "phf_generator",
          "version": "0.11.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_shared@0.11.2",
          "name": "phf_shared",
          "version": "0.11.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.17",
          "name": "ppv-lite86",
          "version": "0.2.17",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.78",
          "name": "proc-macro2",
          "version": "1.0.78",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.35",
          "name": "quote",
          "version": "1.0.35",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.8.5",
          "name": "rand",
          "version": "0.8.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.3.1",
          "name": "rand_chacha",
          "version": "0.3.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.6.4",
          "name": "rand_core",
          "version": "0.6.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_xorshift@0.3.0",
          "name": "rand_xorshift",
          "version": "0.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.10.3",
          "name": "regex",
          "version": "1.10.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.6",
          "name": "regex-automata",
          "version": "0.4.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.2",
          "name": "regex-syntax",
          "version": "0.8.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#siphasher@0.3.11",
          "name": "siphasher",
          "version": "0.3.11",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.52",
          "name": "syn",
          "version": "2.0.52",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.52/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.52"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
          "name": "unicode-ident",
          "version": "1.0.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.11",
          "name": "unicode-width",
          "version": "0.1.11",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.11/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode_names2@1.2.2",
          "name": "unicode_names2",
          "version": "1.2.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2-1.2.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2-1.2.2"
        },
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
          "name": "unicode_names2",
          "version": "1.3.0",
          "manifest_path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode_names2_generator@1.3.0",
          "name": "unicode_names2_generator",
          "version": "1.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_generator-1.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_generator-1.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode_names2_macros@1.1.0",
          "name": "unicode_names2_macros",
          "version": "1.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_macros-1.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode_names2_macros-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
          "name": "wasi",
          "version": "0.11.0+wasi-snapshot-preview1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1"
        }
      ],
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "exit_code": 0,
      "kind": "exec",
      "pid": 684673,
      "ppid": 684501,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "used:cc:b47364ada97c6bc2:fd55da75181da1ab:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
      "pid": 684673,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "used:cc:b47364ada97c6bc2:8fbc204c2de40ae3:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
      "pid": 684673,
      "sha256": "1c1bda37289ec1d821d844082238c8264f2503ddb9285e4c4b35874be718b5b0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "used:cc:b47364ada97c6bc2:8fa1e6b2f28555cd:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
      "pid": 684673,
      "sha256": "5e70191dfb043a5385388b604c5c1feba8fec2b44fdb25873028a427923b8d6a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "used:cc:b47364ada97c6bc2:56ea4f27c87e1fc7:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
      "pid": 684673,
      "sha256": "8197d6a77e8ee592aad69945794d29560ea22f5d99de7fd4a19d8a5ec3c53dd4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "used:cc:b47364ada97c6bc2:6ef887c52156788c:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
      "pid": 684673,
      "sha256": "9f762bbe468a79bebb41c2e60a430efa1e822b7c5745db8269c41350de4cf6f5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
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
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "context_path": "/tmp/native-trace-682693-1783995461657/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-682693-1783995461657/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 684673,
      "ppid": 684501,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp",
        "/target/debug/build/libc-c3c858474dcfa7e6",
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
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcEKTLjp/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-684673-1783995495564756249.map",
      "pid": 684673,
      "ppid": 684501,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-684673-1783995495564756249.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 687077,
      "ppid": 686979,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:a587e75d6d2d30d5:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
      "pid": 687077,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:44aa42a7477a73bf:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "f189463a19503b07293b02eab57bb6a268f722caa1b0fd3bf01819c9e778f96d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:8f581b81fcd1f91d:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "d54965163573b5b6a94bb207e1853ac756c7a6eb0b38a21ada84883adab78a46",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:c020ac05dcd7655a:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "97e49859a3d32ffd27252e0e8539706bc58649b32069e416cbb77967580b65d4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:429a61bb26f8cf41:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "5dc6abe6c5223e7220956797a7a42a04916d6823f5e56ca34d385268f2514eab",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:f4784c2c7bc2094d:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "ae45d2c1fdb5e4bf4b5ab83c5dbbb20cf9793e6066b82b2adf67788724c4bf84",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:52be11ddf2214a50:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "d89ccb939e1883d4dffd86119bb21bf5d1709587ca435e421c9954cf66919888",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:1b02c3e1cda26131:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "c9166dd74f490b2ccd253b27bc29f6a0f1a3ed8bf45783589a74790ff0314599",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:0fd9d30e95dd9fe6:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "2ae6d36184fa6a41b32c3a8fb43aa2c2291e8e5663ef28fe79fe8748969ec580",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:5ff76df10d50778e:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "776d19a30e8b40884c1af49a2c34a554513cd317716009c5d829ee34d62195d0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:d7573de98153f71f:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "af6b4449e342959df2e506900148e1c2d070c2d493aa4b78200da74d5a3828d6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:bb8f99c81bf2ebed:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "a6d24a25a99213780f2ff094d1596912f308236c1f72ff1b2ae35b45e7b9352e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "used:cc:4206ecad076f83f2:4e73252e999d8849:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
      "pid": 687077,
      "sha256": "2ba624871577aaea609c57281a8c0c175c6a5df41b33f4e3b1da3b23bde7d746",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib"
      ],
      "libs": [
        "c",
        "m",
        "rt",
        "pthread",
        "gcc_s",
        "util",
        "rt",
        "pthread",
        "m",
        "dl",
        "c"
      ],
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "context_path": "/tmp/native-trace-682693-1783995461657/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-682693-1783995461657/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 687077,
      "ppid": 686979,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib",
        "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib",
        "/target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib",
        "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib",
        "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib",
        "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib",
        "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib",
        "/target/debug/deps/libppv_lite86-90855b5cb0a3d84e.rlib",
        "/target/debug/deps/librand_core-ea21890b3025e524.rlib",
        "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib",
        "/target/debug/deps/liblibc-6ef22f06d79d59d9.rlib",
        "/target/debug/deps/libcfg_if-4a499ef178f2ff1a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lc",
        "-lm",
        "-lrt",
        "-lpthread",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI",
        "/target/debug/build/unicode_names2-b44907ea69b5d510",
        "/target/debug/deps",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
        "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps"
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
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcUUdDYI/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.0mnogh7.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.05.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.01.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.08.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.04.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.10.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.11.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.12.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.13.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.14.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib(phf_codegen-2be8357290ad31b2.phf_codegen.781f7385c25482d5-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libphf_shared-463e99589cec8ca1.rlib(phf_shared-463e99589cec8ca1.phf_shared.facf40192815ae9c-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libsiphasher-3d4a2c80230e081b.rlib(siphasher-3d4a2c80230e081b.siphasher.504cc0aff0ef069a-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib(rand-fccf93ef6a6b0ceb.rand.d99ab2b3875cfe03-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/librand-fccf93ef6a6b0ceb.rlib(rand-fccf93ef6a6b0ceb.rand.d99ab2b3875cfe03-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib(rand_chacha-4d6cf44e1aa1ed9a.rand_chacha.c8af3e8aa4620bed-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/librand_chacha-4d6cf44e1aa1ed9a.rlib(rand_chacha-4d6cf44e1aa1ed9a.rand_chacha.c8af3e8aa4620bed-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/librand_core-ea21890b3025e524.rlib(rand_core-ea21890b3025e524.rand_core.82143084d8d323ec-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libgetrandom-9f9f6891c3ecf55f.rlib(getrandom-9f9f6891c3ecf55f.getrandom.70e14cb97acd3eb6-cgu.0.rcgu.o",
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
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib(std_detect-e305c7135f50bfab.std_detect.4859ea97f15b1179-cgu.0.rcgu.o",
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
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so",
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
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "/tmp/native-trace-link-cc-687077-1783995524155934565.map",
      "pid": 687077,
      "ppid": 686979,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-687077-1783995524155934565.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
      "parsed_event_count": 853,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 855,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "54d47e50.prost_derive.a5e8fd9e3a8526b6-cgu.14.rcgu.o ...\n59.527  collect2         688362 688361   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGza5Uu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libprost_derive-d5b7106554d47e50.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcPigg2I/raw-dylibs ...\n59.622  ld.lld           688364 688362   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGza5Uu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprost_derive-d5b7106554d47e50.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcPigg2I/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n59.623  rust-lld         688364 688362   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGza5Uu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprost_derive-d5b7106554d47e50.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n60.093  sh               688373 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n60.219  rustc            688377 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cranelift_codegen --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-codegen-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"gimli\" --cfg feature=\"std\" ...\n60.219  rustc            688374 672464   0 \n60.219  cpuUsage.sh      688373 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n60.323  sed              688378 688373   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n60.439  cat              688382 688373   0 /usr/bin/cat /proc/2240539/stat\n60.441  cat              688386 688373   0 /usr/bin/cat /proc/4193716/stat\n60.443  sleep            688387 688373   0 /usr/bin/sleep 1\n60.775  16               688411 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n60.936  frpc             688411 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n61.484  sed              688425 688373   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n61.485  rustc            688424 671759   0 /sbin/rustc --crate-name cranelift_entity --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-entity-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"enable-serde\" --cfg feature=\"serde\" --check-cfg cfg(docsrs,test) ...\n61.577  cat              688431 688373   0 /usr/bin/cat /proc/2240539/stat\n61.577  cat              688433 688373   0 /usr/bin/cat /proc/4193716/stat\n61.617  rustc            688430 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name indexmap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-1.9.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"serde\" --cfg feature=\"serde-1\" --cfg feature=\"std\" ...\n61.725  rustc            688438 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.5.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"indexmap\", \"preserve_order\")) ...\n61.780  rustc            688437 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bincode --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"i128\")) -C metadata=78ed03366453242f ...\n61.967  rustc            688450 684688   0 /usr/local/sbin/rustc --crate-name ureq --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ureq-3.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"_rustls\" --cfg feature=\"_tls\" --cfg feature=\"rustls-no-provider\" ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ureq --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ureq-3.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"_rustls\" --cfg feature=\"_tls\" --cfg feature=\"rustls-no-provider\" ...\n62.018  as               688454 683870   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n62.267  rustc            688461 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prost --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prost-0.14.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"std\" ...\n62.565  riscv64-linux-g  688472 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n62.577  cc1plus          688473 688472   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n62.816  riscv64-linux-g  688482 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n62.816  cc1plus          688483 688482   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n62.817  rustc            688478 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tracing_attributes --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tracing-attributes-0.1.29/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(flaky_tests) --check-cfg ...\n62.817  rustc            688476 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-macros-2.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n62.817  rustc            688481 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name async_trait --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-trait-0.1.88/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n62.822  rustc            688488 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prost_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prost-derive-0.14.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n62.824  rustc            688489 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pin_project_internal --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-internal-1.1.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=clippy::unused_trait_names --warn=unreachable_pub --warn=unnameable_types --warn=unexpected_cfgs ...\n63.142  cargo            688502 686425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n63.208  rustc            688506 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n63.363  as               688516 686257   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-StackIR.o /tmp/ccU0JTjH.s\n63.560  rustc            688522 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n64.232  rustc            688536 671759   0 \n64.295  rustc            688535 672464   0 \n64.347  sh               688537 2147557   0 /bin/sh -c which ps\n64.456  which            688537 2147557   0 /usr/bin/which ps\n64.630  ps               688546 2147557   0 \n64.630  rustc            688541 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prost_types --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prost-types-0.14.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(kani) --cfg feature=\"default\" --cfg ...\n64.630  rustc            688547 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_jit_debug --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-jit-debug-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"gdb_jit_int\" --cfg feature=\"object\" --cfg feature=\"once_cell\" ...\n64.630  sh               688546 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n64.971  rustc            688564 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ppv_lite86 --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"simd\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n64.971  rustc            688561 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=fe406ea3c765137d ...\n64.992  rustc            688563 688502   0 \n65.085  rustc            688572 688502   0 /usr/bin/rustc --crate-name siphasher --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ... /usr/local/sbin/rustc --crate-name siphasher --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n65.088  rustc            688579 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name log --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_s -C metadata=f26460ac6816b597 ...\n65.197  rustc            688583 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name siphasher --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-0.3.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n65.356  cpuUsage.sh      688590 2147557   0 \n65.356  rustc            688587 688502   0 /bin/rustc --crate-name unicode_width --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bench\", \"compiler_builtins\", \"core\", \"default\", \"no_std\", \"rustc-dep-of-std\", \"std\")) ...\n65.356  sed              688598 688590   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n65.356  sh               688590 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n65.482  cat              688603 688590   0 /usr/bin/cat /proc/2240539/stat\n65.554  cat              688606 688590   0 /usr/bin/cat /proc/4193716/stat\n65.554  sleep            688607 688590   0 /usr/bin/sleep 1\n66.558  sed              688618 688590   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n66.788  rustc            688623 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getopts --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\", \"std\")) -C metadata=9a30f0b23db5a9c1 ...\n66.842  cat              688629 688590   0 /usr/bin/cat /proc/2240539/stat\n66.941  cat              688634 688590   0 /usr/bin/cat /proc/4193716/stat\n66.961  as               688636 687343   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/bd3f41d09f19c9b0-ExtractFunction.o /tmp/cc3WIh5R.s\n67.060  rustc            688650 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n67.103  rustc            688652 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n67.690  rustc            688677 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name gimli --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gimli-0.27.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"fallible-iterator\" --cfg feature=\"indexmap\" --cfg feature=\"read\" ...\n67.702  rustc            688678 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name object --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/object-0.30.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"coff\" --cfg feature=\"crc32fast\" --cfg feature=\"elf\" ...\n67.702  rustc            688681 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_shared --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n67.847  rustc            688692 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_shared --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n68.293  powerpc64le-lin  688704 629465   0 /usr/local/sbin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n68.489  as               688710 687136   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/bd3f41d09f19c9b0-FuncCastEmulation.o /tmp/cc9KZHbc.s\n68.708  cc1plus          688705 688704   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/Poppify.cpp ...\n68.940  cc               688708 688561   0 /tmp/native-trace-686425-1783995514820/shims/cc -m64 /target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n69.193  cc               688726 688708   0 /usr/bin/cc -m64 /target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n69.241  collect2         688732 688726   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccR0bHXw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n69.287  ld.lld           688734 688732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccR0bHXw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6 ...\n69.314  rust-lld         688734 688732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccR0bHXw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n69.345  sh               688738 2147557   0 /bin/sh -c which ps\n69.348  which            688738 2147557   0 /usr/bin/which ps\n69.352  sh               688739 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n69.354  ps               688739 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n69.446  rustc            688744 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.11.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"macros\", \"phf_macros\", \"serde\", \"std\", \"uncased\", \"unicase\")) -C metadata=244ba6dc0c36fded ...\n69.492  aarch64-linux-g  688750 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n69.495  cc1plus          688751 688750   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n69.618  cc               688765 688476   0 /tmp/native-trace-682662-1783995461197/shims/cc -Wl,--version-script=/target/debug/deps/rustc754i4h/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc754i4h/symbols.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.0.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.1.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.2.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.3.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.4.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.5.rcgu.o /target/debug/deps/rustc754i4h/rmeta.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.59le7k6awoiay7kpeps9nx9hx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 ...\n69.804  cc               688772 688765   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc754i4h/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc754i4h/symbols.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.0.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.1.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.2.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.3.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.4.rcgu.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.tokio_macros.a96c1e4789de484e-cgu.5.rcgu.o /target/debug/deps/rustc754i4h/rmeta.o /target/debug/deps/tokio_macros-7c36a25fc8e4e5b1.59le7k6awoiay7kpeps9nx9hx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 ...\n69.998  as               688784 629915   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/e951192f0fd9e7b0-cfg.o /tmp/ccqRxHUo.s\n70.017  build-script-bu  688783 688502   0 /target/debug/build/libc-c3c858474dcfa7e6/build-script-build\n70.032  rustc            688786 688783   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n70.069  rustc            688781 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_cache --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-cache-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=f903cf7d75a35212 ...\n70.089  rustc            688793 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=50306f6091620542 ...\n70.134  sh               688796 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n70.136  cpuUsage.sh      688796 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n70.138  sed              688797 688796   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n70.143  cat              688801 688796   0 /usr/bin/cat /proc/2240539/stat\n70.145  cat              688803 688796   0 /usr/bin/cat /proc/4193716/stat\n70.147  sleep            688804 688796   0 \n70.155  rustc            688802 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_environ --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-environ-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"component-model\")) -C metadata=461fac09b7d0875b ...\n70.259  rust-lld         688815 688812   0 \n70.259  collect2         688812 688772   0 \n70.259  ld.lld           688815 688812   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIGbcMT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libtokio_macros-7c36a25fc8e4e5b1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc754i4h/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n70.431  riscv64-linux-g  688808 629151   0 \n70.434  cc1plus          688824 688808   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n70.992  cc               688833 688481   0 /tmp/native-trace-682662-1783995461197/shims/cc -Wl,--version-script=/target/debug/deps/rustcLIs5qr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcLIs5qr/symbols.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.0.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.1.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.2.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.3.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.4.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.5.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.6.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.7.rcgu.o /target/debug/deps/rustcLIs5qr/rmeta.o /target/debug/deps/async_trait-761c3ce8bad53e9b.a6fsmfpscohxzxyo0qix8qvvt.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib ...\n71.090  cc               688837 688833   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcLIs5qr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcLIs5qr/symbols.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.0.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.1.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.2.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.3.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.4.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.5.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.6.rcgu.o /target/debug/deps/async_trait-761c3ce8bad53e9b.async_trait.5fbb56648a8f4e2f-cgu.7.rcgu.o /target/debug/deps/rustcLIs5qr/rmeta.o /target/debug/deps/async_trait-761c3ce8bad53e9b.a6fsmfpscohxzxyo0qix8qvvt.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib ...\n71.148  sed              688841 688796   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n71.150  cat              688842 688796   0 /usr/bin/cat /proc/2240539/stat\n71.153  cat              688844 688796   0 /usr/bin/cat /proc/4193716/stat\n71.175  runc             688836 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process13703616 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n71.199  exe              688855 688836   0 /proc/self/exe init\n71.240  collect2         688838 688837   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaReYaN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libasync_trait-761c3ce8bad53e9b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcLIs5qr/raw-dylibs ...\n71.246  ld.lld           688865 688838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaReYaN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libasync_trait-761c3ce8bad53e9b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcLIs5qr/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n71.250  curl             688857 688836   0 /usr/bin/curl -f http://localhost:9091/healthz\n71.253  rust-lld         688865 688838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaReYaN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libasync_trait-761c3ce8bad53e9b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n72.299  runc             688917 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1642994706 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n72.319  exe              688927 688917   0 /proc/self/exe init\n72.384  etcdctl          688930 688917   0 /usr/local/bin/etcdctl endpoint health\n72.455  aarch64-linux-g  688944 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n72.463  cc1plus          688948 688944   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/Poppify.cpp ...\n73.994  rustc            688975 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getrandom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"rdrand\", \"rustc-dep-of-std\", \"std\", \"test-in-browser ...\n74.191  as               688986 687455   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/bd3f41d09f19c9b0-FuncCastEmulation.o /tmp/cchmEdYk.s\n74.262  rustc            688990 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-1.47.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(fuzzing) --check-cfg cfg(loom) --check-cfg ...\n74.300  cc               688998 688489   0 /tmp/native-trace-682662-1783995461197/shims/cc -Wl,--version-script=/target/debug/deps/rustczulj8m/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustczulj8m/symbols.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.00.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.01.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.02.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.03.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.04.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.05.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.06.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.07.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.08.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.09.rcgu.o /target/debug/deps/rustczulj8m/rmeta.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.9ub9rsopcxv7h1d1xxpdu76pj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib ...\n74.302  cc               688999 688998   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustczulj8m/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustczulj8m/symbols.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.00.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.01.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.02.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.03.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.04.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.05.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.06.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.07.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.08.rcgu.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.pin_project_internal.73a8df0fcb133902-cgu.09.rcgu.o /target/debug/deps/rustczulj8m/rmeta.o /target/debug/deps/pin_project_internal-7c0fe5df944f1a10.9ub9rsopcxv7h1d1xxpdu76pj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-eb530ca7ead29f3a.rlib ...\n74.306  collect2         689000 688999   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJOnYu6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libpin_project_internal-7c0fe5df944f1a10.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustczulj8m/raw-dylibs ...\n74.309  ld.lld           689001 689000   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJOnYu6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpin_project_internal-7c0fe5df944f1a10.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustczulj8m/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n74.313  rust-lld         689001 689000   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJOnYu6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpin_project_internal-7c0fe5df944f1a10.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n74.342  sh               689004 2147557   0 /bin/sh -c which ps\n74.344  which            689004 2147557   0 /usr/bin/which ps\n74.350  sh               689006 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n74.351  ps               689006 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n74.473  sh               689023 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n74.476  cpuUsage.sh      689023 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n74.480  sed              689024 689023   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n74.485  cat              689025 689023   0 /usr/bin/cat /proc/2240539/stat\n74.489  cat              689026 689023   0 /usr/bin/cat /proc/4193716/stat\n74.491  sleep            689027 689023   0 /usr/bin/sleep 1\n74.685  rustc            689032 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"getrandom\" --cfg feature=\"std\" ...\n74.884  cc               689038 688478   0 /tmp/native-trace-682662-1783995461197/shims/cc -Wl,--version-script=/target/debug/deps/rustcCoVT2C/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCoVT2C/symbols.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.00.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.01.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.02.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.03.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.04.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.05.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.06.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.07.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.08.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.09.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.10.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.11.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.12.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.13.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.14.rcgu.o ...\n74.887  cc               689039 689038   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcCoVT2C/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCoVT2C/symbols.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.00.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.01.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.02.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.03.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.04.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.05.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.06.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.07.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.08.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.09.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.10.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.11.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.12.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.13.rcgu.o /target/debug/deps/tracing_attributes-7c7c9daeed01a338.tracing_attributes.15d3951992ad0932-cgu.14.rcgu.o ...\n74.985  collect2         689045 689039   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwOfG76.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libtracing_attributes-7c7c9daeed01a338.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcCoVT2C/raw-dylibs ...\n74.990  ld.lld           689046 689045   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwOfG76.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libtracing_attributes-7c7c9daeed01a338.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcCoVT2C/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n74.999  rust-lld         689046 689045   0 \n75.071  rustc            689047 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio_util --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-util-0.7.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(fuzzing) --check-cfg cfg(loom) --check-cfg ...\n75.076  rustc            689048 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio_stream --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-stream-0.1.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"net\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"fs\", \"full\", \"io-util\", \"net\", \"signal\", \"sync\", \"time\", \"tokio-util\")) ...\n75.379  rustc            689079 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pin_project --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-1.1.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::unused_trait_names --warn=unreachable_pub --warn=unnameable_types --warn=unexpected_cfgs --warn=clippy::undocumented_unsafe_blocks --warn=clippy::transmute_undefined_repr ...\n75.512  cat              689085 689023   0 /usr/bin/cat /proc/4193716/stat\n75.515  as               689081 642532   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/f7deeeb1a9f9c241-module-utils.o /tmp/cctt4Sqr.s\n75.515  sed              689082 689023   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n75.515  cat              689083 689023   0 /usr/bin/cat /proc/2240539/stat\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 684725,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
      "pid": 684725,
      "ppid": 684443,
      "root_cargo_pid": 684443,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 684725,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 684729,
      "ppid": 684725,
      "root_cargo_pid": 684443,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 687139,
      "build_script_target_dir": "unicode_names2-b44907ea69b5d510",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
      "pid": 687139,
      "ppid": 684443,
      "root_cargo_pid": 684443,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "libc",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "bsrun:2b971722f0fa3d65:9d24ac71553b3fba:82a359e119a38779",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "out_dir": "/target/debug/build/libc-c3c858474dcfa7e6/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
      "success": true,
      "target": null,
      "version": "0.2.153",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "unicode_names2",
      "cwd": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "event_id": "bsrun:8946c8a61c9bb131:1a37a2067149b32e:a43ba5a7be190f37",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
      "out_dir": "/target/debug/build/unicode_names2-b44907ea69b5d510/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
      "success": true,
      "target": null,
      "version": "1.3.0",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-aarch64-qwaspk_n/src/unicode_names2-1.3.0",
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
      "build_script_root_pid": 684725,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 684729,
      "ppid": 684725,
      "root_cargo_pid": 684443,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 2561,
    "crate": "unicode_names2",
    "version": "1.3.0",
    "crate_id": "70420",
    "version_id": "1268347",
    "downloads": 4800873,
    "cumulative_downloads": 105018681289,
    "cumulative_share_of_global": 0.3926406051662939,
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
