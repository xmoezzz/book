# `unicode_names2` `1.3.0`

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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru",
    "/target/debug/build/unicode_names2-b44907ea69b5d510",
    "/target/debug/deps",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps"
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
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
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
  "map_path": "/tmp/native-trace-link-cc-690525-1783995592028108250.map",
  "pid": 690525,
  "ppid": 690497,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-690525-1783995592028108250.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "workspace_root": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0"
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
      "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
      "name": "unicode_names2",
      "version": "1.3.0",
      "manifest_path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0"
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
  "pid": 689295,
  "ppid": 689136,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
  "event_id": "used:cc:b47364ada97c6bc2:69e0165584af1e8d:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
  "pid": 689295,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
  "pid": 689295,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
  "pid": 689295,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
  "pid": 689295,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
  "pid": 689295,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
  "context_path": "/tmp/native-trace-687705-1783995534917/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-687705-1783995534917/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 689295,
  "ppid": 689136,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu",
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
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-689295-1783995568165833453.map",
  "pid": 689295,
  "ppid": 689136,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-689295-1783995568165833453.map"
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 690525,
  "ppid": 690497,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:5c82571673755119:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
  "pid": 690525,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:9bd1762d81316c66:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "9f3a97491f955761a77c5e032133bb1a33b0d46ef4e86b02d71d70cd57b62879",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:2708cbd888452296:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "71bdeadaa104734f60ff7364a7da3dbe5c8d827c9d9e5cafa727097d2082dca7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:0e085dccbb5cb9f5:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "ccb34232ac920d378bebf10ece7a2b75947c298fc6addd543d4b7afae8f081d8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:344e033ed647cb86:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "63e87f148db3a864f66dc3f36941520f5f77364571a9c751017f8a1762bb7422",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:9d5ff80154ba7079:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "53f0cca1eca4c8c2594df1cb1942fdcc98bb00038a7ca3dd7a36eedd79618d23",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:8ecbc4445dc65677:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "3c496d4b83311bc2c2298148e4f060bf5d41091664d9bc211937d25fc7f7c77a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:8a3c704035a5a2e4:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "ff992a828c034490b69903897d8958c0b8d35ed8e8f25e46d070f21d8255630e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:0d75025bc05e6d98:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "cf125141ec5e6a751ba6326aa44420c4a5d9340c5296778e76aedbdbb8379562",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:b6eb61c279b0c668:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "0d43e2b0f3acf9673ff02dabfaf51cadd79a2f36c338e40caa3874017a4f8f9d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:7f0300e86edf5dec:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "dd329e1c90a25e3fd2510967af8bcf1bb18fefeb009637e7c36fc784447e0965",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:93dfa57baf30e757:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "b5c25b86e425473da82b01c7a66458db2c1ade5515753ba18d6f988a60a3a563",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "used:cc:ff05ff468a57e113:9d4966e25da9dedb:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
  "pid": 690525,
  "sha256": "2ba624871577aaea609c57281a8c0c175c6a5df41b33f4e3b1da3b23bde7d746",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "context_path": "/tmp/native-trace-687705-1783995534917/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-687705-1783995534917/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 690525,
  "ppid": 690497,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru",
    "/target/debug/build/unicode_names2-b44907ea69b5d510",
    "/target/debug/deps",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
    "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps"
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
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
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
  "map_path": "/tmp/native-trace-link-cc-690525-1783995592028108250.map",
  "pid": 690525,
  "ppid": 690497,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-690525-1783995592028108250.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
  "parsed_event_count": 588,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 590,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "              691296 691231   0 /usr/bin/cat /proc/2240539/stat\n58.836  cat              691298 691231   0 /usr/bin/cat /proc/4193716/stat\n59.174  aarch64-linux-g  691303 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n59.178  cc1plus          691304 691303   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n59.234  as               691305 684325   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n59.291  systemd-sysctl   691309 691308   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdfc3141 --prefix=/net/ipv4/neigh/vethdfc3141 --prefix=/net/ipv6/conf/vethdfc3141 --prefix=/net/ipv6/neigh/vethdfc3141\n59.435  cargo            691315 690424   0 \n59.532  riscv64-linux-g  691314 626155   0 /usr/sbin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n59.602  runc             691319 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1670223064 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n59.611  exe              691327 691319   0 /proc/self/exe init\n59.711  curl             691329 691319   0 /usr/bin/curl -f http://localhost:9091/healthz\n59.744  cc1plus          691335 691314   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n60.032  rustc            691340 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n61.038  rustup           691352 670543   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n61.609  sh               691367 2147557   0 /bin/sh -c which ps\n61.711  which            691367 2147557   0 /usr/bin/which ps\n62.101  sh               691377 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n62.104  ps               691377 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n62.140  rustc            691375 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) ...\n62.180  rustc            691379 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6cee1ea7c2ce8c63 ...\n62.182  rustc            691380 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0919eec9d4c8c0c2 ...\n62.188  rustc            691392 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n62.189  rustc            691382 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) -C metadata=9631560503d11e13 ...\n62.194  rustc            691394 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) ...\n62.199  rustc            691399 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name minimal_lexical --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"compact\", \"default\", \"lint\", \"nightly\", \"std\")) ...\n62.199  rustc            691389 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n62.200  rustc            691395 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"std\" --cfg ...\n62.509  rustc            691400 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=cc8f9a7b2578854f ...\n62.660  rustc            691414 691315   0 \n62.709  rustc            691415 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name home --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/home-0.5.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::all --warn=clippy::correctness --warn=clippy::self_named_module_files --warn=rust_2018_idioms --allow=rustdoc::private_intra_doc_links --warn=clippy::print_stdout ...\n62.759  rustc            691406 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n62.775  sh               691420 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n62.776  cpuUsage.sh      691420 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n62.833  rustc            691429 691315   0 \n62.834  sed              691433 691420   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n62.875  rustc            691435 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.65.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"log\" --cfg feature=\"logging\" ...\n62.924  rustc            691434 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n62.949  cat              691436 691420   0 /usr/bin/cat /proc/2240539/stat\n63.094  cat              691450 691420   0 /usr/bin/cat /proc/4193716/stat\n63.096  sleep            691451 691420   0 /usr/bin/sleep 1\n63.161  runc             691457 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process276207323 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n63.285  cc               691458 691382   0 \n63.291  rustc            691461 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libloading --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(libloading_docs) --check-cfg cfg(target_os, values(\"cygwin\")) --check-cfg ...\n63.357  exe              691472 691457   0 /proc/self/exe init\n63.408  cc               691481 691458   0 /usr/bin/cc -m64 /target/debug/build/prettyplease-a5abfa5892a43be0/rustcjNQZW6/symbols.o /target/debug/build/prettyplease-a5abfa5892a43be0/build_script_build-a5abfa5892a43be0.build_script_build.f2a5d2025795d06d-cgu.0. /target/debug/build/prettyplease-a5abfa5892a43be0/build_script_build-a5abfa5892a43be0.4cag296ndoqvw56bkgf9p6u3v.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n63.465  etcdctl          691474 691457   0 /usr/local/bin/etcdctl endpoint health\n63.468  collect2         691485 691481   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfzp2s8.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n63.492  ld.lld           691490 691485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfzp2s8.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/prettyplease-a5abfa5892a43be0/build_script_build-a5abfa5892a43be0 ...\n63.505  runc             691496 686169   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb --log-format json --systemd-cgroup kill --all 35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb82418 9\n63.511  rust-lld         691490 691485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfzp2s8.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n63.733  runc             691514 686169   0 \n63.753  containerd-shim  691521 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb82418 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb delete\n63.759  runc             691531 691521   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb8241 --log-format json delete --force 35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb82418\n63.778  rustc            691520 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_environ --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-environ-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"component-model\")) -C metadata=725b31a908ecd6a7 ...\n63.843  systemd-sysctl   691539 691538   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth536f5af --prefix=/net/ipv4/neigh/veth536f5af --prefix=/net/ipv6/conf/veth536f5af --prefix=/net/ipv6/neigh/veth536f5af\n63.894  as               691542 646125   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/f7deeeb1a9f9c241-LocalGraph.o /tmp/ccw5PuE8.s\n63.918  cc               691544 691375   0 /tmp/native-trace-690424-1783995586159/shims/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustcPmXhkS/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n63.935  cc               691550 691544   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustcPmXhkS/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n63.945  rustc            691548 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazycell --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"clippy\", \"nightly\", \"nightly-testing\", \"serde\")) -C metadata=4ad32744f67d8797 ...\n64.056  rustc            691561 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_cranelift --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-cranelift-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all-arch\", \"component-model\", \"incremental-cache\")) -C metadata=02a9faefb34be8c1 ...\n64.098  sed              691563 691420   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n64.102  cat              691564 691420   0 /usr/bin/cat /proc/2240539/stat\n64.105  cat              691566 691420   0 \n64.171  collect2         691572 691550   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczpDe3F.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n64.214  ld.lld           691573 691572   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczpDe3F.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160 ...\n64.236  rustc            691577 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazy_static --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"spin\", \"spin_no_std\")) -C metadata=9c1da1701740b720 ...\n64.318  cc               691574 691392   0 /tmp/native-trace-690424-1783995586159/shims/cc -m64 /target/debug/build/libc-6f46b2e82bfaccdd/rustczYDqro/symbols.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.0.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.1.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.2.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.3.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.c2i38v5ac7kzefenjsa5uhn1o.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n64.318  rust-lld         691573 691572   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczpDe3F.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n64.335  cc               691585 691574   0 /usr/bin/cc -m64 /target/debug/build/libc-6f46b2e82bfaccdd/rustczYDqro/symbols.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.0.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.1.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.2.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.3.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.c2i38v5ac7kzefenjsa5uhn1o.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n64.372  ld.lld           691587 691586   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPAM6HB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd ...\n64.372  as               691589 645838   0 \n64.374  collect2         691586 691585   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPAM6HB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n64.385  rust-lld         691587 691586   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPAM6HB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n64.389  rustc            691590 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustc_hash --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-hash-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n64.472  rustc            691595 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-1.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(hyper_unstable_tracing) --check-cfg cfg(hyper_unstable_ffi) --cfg ...\n64.624  as               691606 665968   0 \n64.856  rustc            691627 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name log --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_s -C metadata=cdfd7a6d1c7e8d5d ...\n64.893  rustc            691638 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name peeking_take_while --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/peeking_take_while-0.1.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6aeb426e6d813e8c ...\n64.943  aarch64-linux-g  691644 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n65.000  rustc            691648 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"default\", \"example_generated\", \"rustc-dep-of-std\")) ...\n65.119  cc1plus          691669 691644   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/Directize.cpp ...\n65.216  rustc            691683 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n65.329  build-script-bu  691694 691315   0 /target/debug/build/prettyplease-a5abfa5892a43be0/build-script-build\n65.341  cc               691696 691435   0 /tmp/native-trace-690424-1783995586159/shims/cc -m64 /target/debug/build/bindgen-0fd0307a344b9743/rustcyY3Eir/symbols.o /target/debug/build/bindgen-0fd0307a344b9743/build_script_build-0fd0307a344b9743.build_script_build.39445bfa37f6835d-cgu.0.rcgu. /target/debug/build/bindgen-0fd0307a344b9743/build_script_build-0fd0307a344b9743.1vjbcw3k6p78ub2gyd594l2iq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n65.344  cc               691697 691696   0 /usr/bin/cc -m64 /target/debug/build/bindgen-0fd0307a344b9743/rustcyY3Eir/symbols.o /target/debug/build/bindgen-0fd0307a344b9743/build_script_build-0fd0307a344b9743.build_script_build.39445bfa37f6835d-cgu.0.rcgu. /target/debug/build/bindgen-0fd0307a344b9743/build_script_build-0fd0307a344b9743.1vjbcw3k6p78ub2gyd594l2iq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n65.350  collect2         691698 691697   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccygdUhG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n65.360  ld.lld           691705 691698   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccygdUhG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/bindgen-0fd0307a344b9743/build_script_build-0fd0307a344b9743 ...\n65.367  rust-lld         691705 691698   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccygdUhG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n65.386  as               691707 690702   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/bd3f41d09f19c9b0-InstrumentLocals.o /tmp/ccnahxjO.s\n65.595  rustc            691736 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper_timeout --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-timeout-0.5.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=eef1945e173266c2 ...\n66.021  rustc            691758 691756   0 \n66.021  build-script-bu  691756 691315   0 /target/debug/build/proc-macro2-8db20fd562093160/build-script-build\n66.021  rustc            691757 691755   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n66.021  build-script-bu  691755 691315   0 /target/debug/build/libc-6f46b2e82bfaccdd/build-script-build\n66.021  ld.lld           691752 691751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpleoUA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-96d75258d9247a3e/build_script_build-96d75258d9247a3e ...\n66.021  rust-lld         691752 691751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpleoUA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n66.022  rustc            691782 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n66.022  cc               691749 691394   0 /tmp/native-trace-690424-1783995586159/shims/cc -m64 /target/debug/build/quote-96d75258d9247a3e/rustcUuQaNm/symbols.o /target/debug/build/quote-96d75258d9247a3e/build_script_build-96d75258d9247a3e.build_script_build.fb115e36fc673bbe-cgu.0.rcgu.o /target/debug/build/quote-96d75258d9247a3e/build_script_build-96d75258d9247a3e.1y4cojsebyqz206k2kdch1ynu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n66.022  collect2         691751 691750   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpleoUA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n66.022  cc               691750 691749   0 /usr/bin/cc -m64 /target/debug/build/quote-96d75258d9247a3e/rustcUuQaNm/symbols.o /target/debug/build/quote-96d75258d9247a3e/build_script_build-96d75258d9247a3e.build_script_build.fb115e36fc673bbe-cgu.0.rcgu.o /target/debug/build/quote-96d75258d9247a3e/build_script_build-96d75258d9247a3e.1y4cojsebyqz206k2kdch1ynu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n66.062  cc               691785 691389   0 /tmp/native-trace-690424-1783995586159/shims/cc -m64 /target/debug/build/rustix-fcdb8bb79481d867/rustc7u4jJ6/symbols.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.0.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.1.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.2.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.0x41plzb1g0kobng8hvuq54rg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n66.064  cc               691786 691785   0 /usr/bin/cc -m64 /target/debug/build/rustix-fcdb8bb79481d867/rustc7u4jJ6/symbols.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.0.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.1.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.2.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.0x41plzb1g0kobng8hvuq54rg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n66.068  collect2         691788 691786   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6ttJEv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n66.071  ld.lld           691789 691788   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6ttJEv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867 ...\n66.081  rust-lld         691789 691788   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6ttJEv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n66.085  rustc            691791 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clang_3_5\" --cfg feature=\"clang_3_6\" --cfg feature=\"clang_3_7\" ...\n66.135  rustc            691783 691756   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-e7e1e42d0fb0a024/out/probe src/probe/proc_macro_span.rs --target x86_64-unknown-linux-gnu\n66.395  riscv64-linux-g  691813 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n66.493  cc1plus          691826 691813   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n66.642  build-script-bu  691831 691315   0 /target/debug/build/rustix-fcdb8bb79481d867/build-script-build\n66.649  rustc            691832 691831   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target x86_64-unknown-linux-gnu -o - -\n66.676  build-script-bu  691835 691315   0 /target/debug/build/quote-96d75258d9247a3e/build-script-build\n66.680  rustc            691838 691835   0 /sbin/rustc --version\n66.709  rustc            691837 691756   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-e7e1e42d0fb0a024/out/probe src/probe/proc_macro_span_location.rs --target x86_64-unknown-linux-gnu\n66.764  sh               691829 2147557   0 /bin/sh -c which ps\n66.766  which            691829 2147557   0 /usr/bin/which ps\n66.849  sh               691854 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n66.849  ps               691854 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n66.869  rustc            691853 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tonic --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tonic-0.14.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --deny=clippy::uninlined_format_args --warn=rust_2018_idioms --warn=missing_docs --warn=missing_debug_implementations --deny=rustdoc::broken_intra_doc_links ...\n66.877  rustc            691857 691756   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-e7e1e42d0fb0a024/out/probe src/probe/proc_macro_span_file.rs --target x86_64-unknown-linux-gnu\n67.033  sh               691863 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n67.036  cpuUsage.sh      691863 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n67.038  rustc            691862 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) ...\n67.040  cat              691865 691863   0 /usr/bin/cat /proc/2240539/stat\n67.046  cat              691866 691863   0 \n67.046  sleep            691867 691863   0 /usr/bin/sleep 1\n67.047  sed              691864 691863   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n67.075  aarch64-linux-g  691868 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n67.101  rustc            691872 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustix --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n67.207  cc1plus          691869 691868   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/Untee.cpp ...\n67.314  rustc            691880 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name nom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/nom-7.1.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n"
}
```

#### Record 30

```json
{
  "argv": [
    "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 689326,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
  "pid": 689326,
  "ppid": 689095,
  "root_cargo_pid": 689095,
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
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 689326,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "rustc",
  "pid": 689327,
  "ppid": 689326,
  "root_cargo_pid": 689095,
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
  "build_script_root_pid": 690612,
  "build_script_target_dir": "unicode_names2-b44907ea69b5d510",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
  "pid": 690612,
  "ppid": 689095,
  "root_cargo_pid": 689095,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
  "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "event_id": "bsrun:efef4070b339d702:1a37a2067149b32e:a43ba5a7be190f37",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
  "out_dir": "/target/debug/build/unicode_names2-b44907ea69b5d510/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
  "success": true,
  "target": null,
  "version": "1.3.0",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 35

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 689326,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "rustc",
  "pid": 689327,
  "ppid": 689326,
  "root_cargo_pid": 689095,
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
  "time": "2026-07-14T02:20:34.244011+00:00",
  "crate": "unicode_names2",
  "version": "1.3.0",
  "architecture": "ppc64le",
  "duration_seconds": 112.47606866061687,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "manifest_path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "workspace_root": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0"
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
          "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
          "name": "unicode_names2",
          "version": "1.3.0",
          "manifest_path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0"
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
      "pid": 689295,
      "ppid": 689136,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
      "event_id": "used:cc:b47364ada97c6bc2:69e0165584af1e8d:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
      "pid": 689295,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
      "pid": 689295,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
      "pid": 689295,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
      "pid": 689295,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
      "pid": 689295,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
      "context_path": "/tmp/native-trace-687705-1783995534917/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-687705-1783995534917/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 689295,
      "ppid": 689136,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/raw-dylibs",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu",
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
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustctcbNYu/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-689295-1783995568165833453.map",
      "pid": 689295,
      "ppid": 689136,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-689295-1783995568165833453.map"
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 690525,
      "ppid": 690497,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:5c82571673755119:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
      "pid": 690525,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:9bd1762d81316c66:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "9f3a97491f955761a77c5e032133bb1a33b0d46ef4e86b02d71d70cd57b62879",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:2708cbd888452296:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "71bdeadaa104734f60ff7364a7da3dbe5c8d827c9d9e5cafa727097d2082dca7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:0e085dccbb5cb9f5:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "ccb34232ac920d378bebf10ece7a2b75947c298fc6addd543d4b7afae8f081d8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:344e033ed647cb86:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "63e87f148db3a864f66dc3f36941520f5f77364571a9c751017f8a1762bb7422",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:9d5ff80154ba7079:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "53f0cca1eca4c8c2594df1cb1942fdcc98bb00038a7ca3dd7a36eedd79618d23",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:8ecbc4445dc65677:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "3c496d4b83311bc2c2298148e4f060bf5d41091664d9bc211937d25fc7f7c77a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:8a3c704035a5a2e4:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "ff992a828c034490b69903897d8958c0b8d35ed8e8f25e46d070f21d8255630e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:0d75025bc05e6d98:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "cf125141ec5e6a751ba6326aa44420c4a5d9340c5296778e76aedbdbb8379562",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:b6eb61c279b0c668:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "0d43e2b0f3acf9673ff02dabfaf51cadd79a2f36c338e40caa3874017a4f8f9d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:7f0300e86edf5dec:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "dd329e1c90a25e3fd2510967af8bcf1bb18fefeb009637e7c36fc784447e0965",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:93dfa57baf30e757:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "b5c25b86e425473da82b01c7a66458db2c1ade5515753ba18d6f988a60a3a563",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "used:cc:ff05ff468a57e113:9d4966e25da9dedb:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
      "pid": 690525,
      "sha256": "2ba624871577aaea609c57281a8c0c175c6a5df41b33f4e3b1da3b23bde7d746",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "context_path": "/tmp/native-trace-687705-1783995534917/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-687705-1783995534917/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 690525,
      "ppid": 690497,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru",
        "/target/debug/build/unicode_names2-b44907ea69b5d510",
        "/target/debug/deps",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
        "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps"
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
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o",
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
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254700           254700       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254750           254750       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547a0           2547a0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2547f0           2547f0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254840           254840       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2548e0           2548e0       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254980           254980       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254a20           254a20       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254c90           254c90        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/254ca0           254ca0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/263f60           263f60        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/2704b0           2704b0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/270b40           270b40        9    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/27d780           27d780        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286510           286510       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286590           286590       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286610           286610       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/286690           286690       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28afd0           28afd0       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b0b0           28b0b0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b190           28b190       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/28b270           28b270       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c6d0           29c6d0       42    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c720           29c720       12    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c740           29c740        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c750           29c750       13    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c770           29c770       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7a0           29c7a0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c7d0           29c7d0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29c800           29c800       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1a0           29d1a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d1e0           29d1e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d2c0           29d2c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d430           29d430        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d480           29d480        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d490           29d490        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4b0           29d4b0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d590           29d590        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5a0           29d5a0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5c0           29d5c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29d5e0           29d5e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e5f0           29e5f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0/29e610           29e610        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
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
      "map_path": "/tmp/native-trace-link-cc-690525-1783995592028108250.map",
      "pid": 690525,
      "ppid": 690497,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-690525-1783995592028108250.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
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
      "parsed_event_count": 588,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 590,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "              691296 691231   0 /usr/bin/cat /proc/2240539/stat\n58.836  cat              691298 691231   0 /usr/bin/cat /proc/4193716/stat\n59.174  aarch64-linux-g  691303 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n59.178  cc1plus          691304 691303   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n59.234  as               691305 684325   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n59.291  systemd-sysctl   691309 691308   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdfc3141 --prefix=/net/ipv4/neigh/vethdfc3141 --prefix=/net/ipv6/conf/vethdfc3141 --prefix=/net/ipv6/neigh/vethdfc3141\n59.435  cargo            691315 690424   0 \n59.532  riscv64-linux-g  691314 626155   0 /usr/sbin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n59.602  runc             691319 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1670223064 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n59.611  exe              691327 691319   0 /proc/self/exe init\n59.711  curl             691329 691319   0 /usr/bin/curl -f http://localhost:9091/healthz\n59.744  cc1plus          691335 691314   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n60.032  rustc            691340 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n61.038  rustup           691352 670543   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n61.609  sh               691367 2147557   0 /bin/sh -c which ps\n61.711  which            691367 2147557   0 /usr/bin/which ps\n62.101  sh               691377 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n62.104  ps               691377 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n62.140  rustc            691375 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) ...\n62.180  rustc            691379 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6cee1ea7c2ce8c63 ...\n62.182  rustc            691380 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0919eec9d4c8c0c2 ...\n62.188  rustc            691392 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n62.189  rustc            691382 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) -C metadata=9631560503d11e13 ...\n62.194  rustc            691394 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) ...\n62.199  rustc            691399 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name minimal_lexical --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"compact\", \"default\", \"lint\", \"nightly\", \"std\")) ...\n62.199  rustc            691389 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n62.200  rustc            691395 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"std\" --cfg ...\n62.509  rustc            691400 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=cc8f9a7b2578854f ...\n62.660  rustc            691414 691315   0 \n62.709  rustc            691415 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name home --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/home-0.5.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::all --warn=clippy::correctness --warn=clippy::self_named_module_files --warn=rust_2018_idioms --allow=rustdoc::private_intra_doc_links --warn=clippy::print_stdout ...\n62.759  rustc            691406 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n62.775  sh               691420 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n62.776  cpuUsage.sh      691420 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n62.833  rustc            691429 691315   0 \n62.834  sed              691433 691420   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n62.875  rustc            691435 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.65.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"log\" --cfg feature=\"logging\" ...\n62.924  rustc            691434 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n62.949  cat              691436 691420   0 /usr/bin/cat /proc/2240539/stat\n63.094  cat              691450 691420   0 /usr/bin/cat /proc/4193716/stat\n63.096  sleep            691451 691420   0 /usr/bin/sleep 1\n63.161  runc             691457 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process276207323 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n63.285  cc               691458 691382   0 \n63.291  rustc            691461 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libloading --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(libloading_docs) --check-cfg cfg(target_os, values(\"cygwin\")) --check-cfg ...\n63.357  exe              691472 691457   0 /proc/self/exe init\n63.408  cc               691481 691458   0 /usr/bin/cc -m64 /target/debug/build/prettyplease-a5abfa5892a43be0/rustcjNQZW6/symbols.o /target/debug/build/prettyplease-a5abfa5892a43be0/build_script_build-a5abfa5892a43be0.build_script_build.f2a5d2025795d06d-cgu.0. /target/debug/build/prettyplease-a5abfa5892a43be0/build_script_build-a5abfa5892a43be0.4cag296ndoqvw56bkgf9p6u3v.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n63.465  etcdctl          691474 691457   0 /usr/local/bin/etcdctl endpoint health\n63.468  collect2         691485 691481   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfzp2s8.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n63.492  ld.lld           691490 691485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfzp2s8.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/prettyplease-a5abfa5892a43be0/build_script_build-a5abfa5892a43be0 ...\n63.505  runc             691496 686169   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb --log-format json --systemd-cgroup kill --all 35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb82418 9\n63.511  rust-lld         691490 691485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfzp2s8.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n63.733  runc             691514 686169   0 \n63.753  containerd-shim  691521 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb82418 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb delete\n63.759  runc             691531 691521   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb8241 --log-format json delete --force 35579914cdf442ec078d7318d8f3a64ec74abf612c666ba4c95636d9abb82418\n63.778  rustc            691520 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_environ --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-environ-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"component-model\")) -C metadata=725b31a908ecd6a7 ...\n63.843  systemd-sysctl   691539 691538   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth536f5af --prefix=/net/ipv4/neigh/veth536f5af --prefix=/net/ipv6/conf/veth536f5af --prefix=/net/ipv6/neigh/veth536f5af\n63.894  as               691542 646125   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/f7deeeb1a9f9c241-LocalGraph.o /tmp/ccw5PuE8.s\n63.918  cc               691544 691375   0 /tmp/native-trace-690424-1783995586159/shims/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustcPmXhkS/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n63.935  cc               691550 691544   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustcPmXhkS/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n63.945  rustc            691548 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazycell --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"clippy\", \"nightly\", \"nightly-testing\", \"serde\")) -C metadata=4ad32744f67d8797 ...\n64.056  rustc            691561 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_cranelift --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-cranelift-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all-arch\", \"component-model\", \"incremental-cache\")) -C metadata=02a9faefb34be8c1 ...\n64.098  sed              691563 691420   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n64.102  cat              691564 691420   0 /usr/bin/cat /proc/2240539/stat\n64.105  cat              691566 691420   0 \n64.171  collect2         691572 691550   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczpDe3F.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n64.214  ld.lld           691573 691572   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczpDe3F.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160 ...\n64.236  rustc            691577 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazy_static --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"spin\", \"spin_no_std\")) -C metadata=9c1da1701740b720 ...\n64.318  cc               691574 691392   0 /tmp/native-trace-690424-1783995586159/shims/cc -m64 /target/debug/build/libc-6f46b2e82bfaccdd/rustczYDqro/symbols.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.0.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.1.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.2.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.3.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.c2i38v5ac7kzefenjsa5uhn1o.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n64.318  rust-lld         691573 691572   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczpDe3F.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n64.335  cc               691585 691574   0 /usr/bin/cc -m64 /target/debug/build/libc-6f46b2e82bfaccdd/rustczYDqro/symbols.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.0.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.1.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.2.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.build_script_build.13c74f0e3363ba3b-cgu.3.rcgu.o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd.c2i38v5ac7kzefenjsa5uhn1o.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n64.372  ld.lld           691587 691586   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPAM6HB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-6f46b2e82bfaccdd/build_script_build-6f46b2e82bfaccdd ...\n64.372  as               691589 645838   0 \n64.374  collect2         691586 691585   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPAM6HB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n64.385  rust-lld         691587 691586   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPAM6HB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n64.389  rustc            691590 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustc_hash --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-hash-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n64.472  rustc            691595 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-1.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(hyper_unstable_tracing) --check-cfg cfg(hyper_unstable_ffi) --cfg ...\n64.624  as               691606 665968   0 \n64.856  rustc            691627 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name log --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_s -C metadata=cdfd7a6d1c7e8d5d ...\n64.893  rustc            691638 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name peeking_take_while --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/peeking_take_while-0.1.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6aeb426e6d813e8c ...\n64.943  aarch64-linux-g  691644 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n65.000  rustc            691648 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"default\", \"example_generated\", \"rustc-dep-of-std\")) ...\n65.119  cc1plus          691669 691644   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/Directize.cpp ...\n65.216  rustc            691683 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n65.329  build-script-bu  691694 691315   0 /target/debug/build/prettyplease-a5abfa5892a43be0/build-script-build\n65.341  cc               691696 691435   0 /tmp/native-trace-690424-1783995586159/shims/cc -m64 /target/debug/build/bindgen-0fd0307a344b9743/rustcyY3Eir/symbols.o /target/debug/build/bindgen-0fd0307a344b9743/build_script_build-0fd0307a344b9743.build_script_build.39445bfa37f6835d-cgu.0.rcgu. /target/debug/build/bindgen-0fd0307a344b9743/build_script_build-0fd0307a344b9743.1vjbcw3k6p78ub2gyd594l2iq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n65.344  cc               691697 691696   0 /usr/bin/cc -m64 /target/debug/build/bindgen-0fd0307a344b9743/rustcyY3Eir/symbols.o /target/debug/build/bindgen-0fd0307a344b9743/build_script_build-0fd0307a344b9743.build_script_build.39445bfa37f6835d-cgu.0.rcgu. /target/debug/build/bindgen-0fd0307a344b9743/build_script_build-0fd0307a344b9743.1vjbcw3k6p78ub2gyd594l2iq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n65.350  collect2         691698 691697   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccygdUhG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n65.360  ld.lld           691705 691698   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccygdUhG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/bindgen-0fd0307a344b9743/build_script_build-0fd0307a344b9743 ...\n65.367  rust-lld         691705 691698   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccygdUhG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n65.386  as               691707 690702   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/bd3f41d09f19c9b0-InstrumentLocals.o /tmp/ccnahxjO.s\n65.595  rustc            691736 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper_timeout --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-timeout-0.5.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=eef1945e173266c2 ...\n66.021  rustc            691758 691756   0 \n66.021  build-script-bu  691756 691315   0 /target/debug/build/proc-macro2-8db20fd562093160/build-script-build\n66.021  rustc            691757 691755   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n66.021  build-script-bu  691755 691315   0 /target/debug/build/libc-6f46b2e82bfaccdd/build-script-build\n66.021  ld.lld           691752 691751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpleoUA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-96d75258d9247a3e/build_script_build-96d75258d9247a3e ...\n66.021  rust-lld         691752 691751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpleoUA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n66.022  rustc            691782 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n66.022  cc               691749 691394   0 /tmp/native-trace-690424-1783995586159/shims/cc -m64 /target/debug/build/quote-96d75258d9247a3e/rustcUuQaNm/symbols.o /target/debug/build/quote-96d75258d9247a3e/build_script_build-96d75258d9247a3e.build_script_build.fb115e36fc673bbe-cgu.0.rcgu.o /target/debug/build/quote-96d75258d9247a3e/build_script_build-96d75258d9247a3e.1y4cojsebyqz206k2kdch1ynu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n66.022  collect2         691751 691750   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpleoUA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n66.022  cc               691750 691749   0 /usr/bin/cc -m64 /target/debug/build/quote-96d75258d9247a3e/rustcUuQaNm/symbols.o /target/debug/build/quote-96d75258d9247a3e/build_script_build-96d75258d9247a3e.build_script_build.fb115e36fc673bbe-cgu.0.rcgu.o /target/debug/build/quote-96d75258d9247a3e/build_script_build-96d75258d9247a3e.1y4cojsebyqz206k2kdch1ynu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n66.062  cc               691785 691389   0 /tmp/native-trace-690424-1783995586159/shims/cc -m64 /target/debug/build/rustix-fcdb8bb79481d867/rustc7u4jJ6/symbols.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.0.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.1.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.2.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.0x41plzb1g0kobng8hvuq54rg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n66.064  cc               691786 691785   0 /usr/bin/cc -m64 /target/debug/build/rustix-fcdb8bb79481d867/rustc7u4jJ6/symbols.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.0.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.1.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.build_script_build.7e242d322d29069-cgu.2.rcgu.o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867.0x41plzb1g0kobng8hvuq54rg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n66.068  collect2         691788 691786   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6ttJEv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n66.071  ld.lld           691789 691788   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6ttJEv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rustix-fcdb8bb79481d867/build_script_build-fcdb8bb79481d867 ...\n66.081  rust-lld         691789 691788   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6ttJEv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n66.085  rustc            691791 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clang_3_5\" --cfg feature=\"clang_3_6\" --cfg feature=\"clang_3_7\" ...\n66.135  rustc            691783 691756   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-e7e1e42d0fb0a024/out/probe src/probe/proc_macro_span.rs --target x86_64-unknown-linux-gnu\n66.395  riscv64-linux-g  691813 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n66.493  cc1plus          691826 691813   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n66.642  build-script-bu  691831 691315   0 /target/debug/build/rustix-fcdb8bb79481d867/build-script-build\n66.649  rustc            691832 691831   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target x86_64-unknown-linux-gnu -o - -\n66.676  build-script-bu  691835 691315   0 /target/debug/build/quote-96d75258d9247a3e/build-script-build\n66.680  rustc            691838 691835   0 /sbin/rustc --version\n66.709  rustc            691837 691756   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-e7e1e42d0fb0a024/out/probe src/probe/proc_macro_span_location.rs --target x86_64-unknown-linux-gnu\n66.764  sh               691829 2147557   0 /bin/sh -c which ps\n66.766  which            691829 2147557   0 /usr/bin/which ps\n66.849  sh               691854 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n66.849  ps               691854 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n66.869  rustc            691853 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tonic --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tonic-0.14.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --deny=clippy::uninlined_format_args --warn=rust_2018_idioms --warn=missing_docs --warn=missing_debug_implementations --deny=rustdoc::broken_intra_doc_links ...\n66.877  rustc            691857 691756   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-e7e1e42d0fb0a024/out/probe src/probe/proc_macro_span_file.rs --target x86_64-unknown-linux-gnu\n67.033  sh               691863 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n67.036  cpuUsage.sh      691863 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n67.038  rustc            691862 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) ...\n67.040  cat              691865 691863   0 /usr/bin/cat /proc/2240539/stat\n67.046  cat              691866 691863   0 \n67.046  sleep            691867 691863   0 /usr/bin/sleep 1\n67.047  sed              691864 691863   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n67.075  aarch64-linux-g  691868 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n67.101  rustc            691872 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustix --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n67.207  cc1plus          691869 691868   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/Untee.cpp ...\n67.314  rustc            691880 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name nom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/nom-7.1.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 689326,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
      "pid": 689326,
      "ppid": 689095,
      "root_cargo_pid": 689095,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 689326,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "rustc",
      "pid": 689327,
      "ppid": 689326,
      "root_cargo_pid": 689095,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 690612,
      "build_script_target_dir": "unicode_names2-b44907ea69b5d510",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
      "pid": 690612,
      "ppid": 689095,
      "root_cargo_pid": 689095,
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
      "cwd": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "event_id": "bsrun:efef4070b339d702:1a37a2067149b32e:a43ba5a7be190f37",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
      "out_dir": "/target/debug/build/unicode_names2-b44907ea69b5d510/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
      "success": true,
      "target": null,
      "version": "1.3.0",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ac3j4_nh/src/unicode_names2-1.3.0",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 689326,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "rustc",
      "pid": 689327,
      "ppid": 689326,
      "root_cargo_pid": 689095,
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
