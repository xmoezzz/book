# `unicode_names2` `1.3.0`

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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c",
    "/target/debug/build/unicode_names2-b44907ea69b5d510",
    "/target/debug/deps",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/lib64",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254630           254630       4f    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254680           254680       4f    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2546d0           2546d0       4f    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254720           254720       4f    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254770           254770       93    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254810           254810       93    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2548b0           2548b0       93    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254950           254950       93    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bc0           254bc0        5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bd0           254bd0        5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/263e90           263e90        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2703e0           2703e0        5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/270a70           270a70        9    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/27d6b0           27d6b0        5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286440           286440       71    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2864c0           2864c0       71    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286540           286540       71    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2865c0           2865c0       71    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28af00           28af00       d5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28afe0           28afe0       de    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b0c0           28b0c0       d5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b1a0           28b1a0       de    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c600           29c600       42    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c650           29c650       12    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c670           29c670        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c680           29c680       13    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6a0           29c6a0       26    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6d0           29c6d0       26    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c700           29c700       26    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c730           29c730       26    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d0d0           29d0d0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d110           29d110        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d1f0           29d1f0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d280           29d280        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d360           29d360        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3b0           29d3b0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3c0           29d3c0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3e0           29d3e0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4c0           29d4c0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4d0           29d4d0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d510           29d510        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e520           29e520        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e540           29e540        d    16         /target/debug/deps"
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
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
      "directory": "/lib64",
      "kind": "dynamic_library",
      "path": "/lib64/ld-linux-x86-64.so.2",
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
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1",
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
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254630           254630       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254630           254630       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254680           254680       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254680           254680       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2546d0           2546d0       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2546d0           2546d0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254720           254720       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254720           254720       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254770           254770       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254770           254770       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254810           254810       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254810           254810       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2548b0           2548b0       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2548b0           2548b0       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254950           254950       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254950           254950       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bc0           254bc0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bc0           254bc0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bd0           254bd0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bd0           254bd0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/263e90           263e90        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/263e90           263e90        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2703e0           2703e0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2703e0           2703e0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/270a70           270a70        9    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/270a70           270a70        9    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/27d6b0           27d6b0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/27d6b0           27d6b0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286440           286440       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286440           286440       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2864c0           2864c0       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2864c0           2864c0       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286540           286540       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286540           286540       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2865c0           2865c0       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2865c0           2865c0       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28af00           28af00       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28af00           28af00       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28afe0           28afe0       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28afe0           28afe0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b0c0           28b0c0       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b0c0           28b0c0       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b1a0           28b1a0       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b1a0           28b1a0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c600           29c600       42    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c600           29c600       42    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c650           29c650       12    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c650           29c650       12    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c670           29c670        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c670           29c670        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c680           29c680       13    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c680           29c680       13    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6a0           29c6a0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6a0           29c6a0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6d0           29c6d0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6d0           29c6d0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c700           29c700       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c700           29c700       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c730           29c730       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c730           29c730       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d0d0           29d0d0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d0d0           29d0d0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d110           29d110        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d110           29d110        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d1f0           29d1f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d1f0           29d1f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d280           29d280        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d280           29d280        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d360           29d360        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d360           29d360        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3b0           29d3b0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3b0           29d3b0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3c0           29d3c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3c0           29d3c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3e0           29d3e0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3e0           29d3e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4c0           29d4c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4c0           29d4c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4d0           29d4d0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4d0           29d4d0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d510           29d510        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d510           29d510        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e520           29e520        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e520           29e520        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e540           29e540        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e540           29e540        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
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
  "map_path": "/tmp/native-trace-link-cc-690365-1783995585586588126.map",
  "pid": 690365,
  "ppid": 690173,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-690365-1783995585586588126.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "workspace_root": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0"
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
      "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
      "name": "unicode_names2",
      "version": "1.3.0",
      "manifest_path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0"
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
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
  "pid": 688708,
  "ppid": 688561,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
  "event_id": "used:cc:b47364ada97c6bc2:7e3a41dcf0a59539:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
  "pid": 688708,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
  "pid": 688708,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
  "pid": 688708,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
  "pid": 688708,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
  "pid": 688708,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
  "context_path": "/tmp/native-trace-686425-1783995514820/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-686425-1783995514820/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 688708,
  "ppid": 688561,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL",
    "/target/debug/build/libc-c3c858474dcfa7e6",
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
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-688708-1783995558156278642.map",
  "pid": 688708,
  "ppid": 688561,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-688708-1783995558156278642.map"
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 690365,
  "ppid": 690173,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:d39869de7258019e:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
  "pid": 690365,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:ddb5541122ee3513:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "6c8f28bbb543a4de0fd24b4f714e14e13020f9a077cae4a2387242f2e8351f07",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:fc361c6b9238d5a5:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "862eb4261f6b79c74ea2452fc70b5ead0ed8f05ade85b0bfcee503a7b6cd51d3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:a0e8d701ee8fe006:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "2cbd08eab74e3371f88a174a55723469393a480500ad8d2900223d363981f19e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:2ab9838a77614eb3:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "250a9cbf054f76a0f94597ff792f8023573c1719b9b3ef9fe1e8b9b9c73460a6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:01b92da1903c09e2:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "a30e56818f153d1765f7344747c2e4ef99fbefef09b5f16a4bb94d19d3254714",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:a54bd33b7ff25dcd:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "8bcc8d9fa738d8b561857e094bd44f3c5f334168e24af012b412cbcac61fa871",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:1bf74e97bb58c9ec:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "82b1bf11e045c5a3ba27d7b435989950aabdabbde330b9eebb982cf0375d736e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:2ec006aa4ff0bafd:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "85ca4d23564d146b631e29091301ab134d96c92e66870947d4ac8b8840bb2b88",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:f36ba7d17d906d28:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "dc6423d1bc33a0cfae506729d075a53dd9d7921d1bec55acb86b12634d60f91b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:b16d78712e0ddda8:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "17c0839845ee8fbd95ed7c22cbc0cd5d8033f0355b5d677c981a9e40408a641b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:e7f2cf85bc8e0700:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "28419972c73e42d65c64bb3c03652af56685036cacbf23a12041be4284e30523",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "used:cc:94e6a9108277b074:5fad05daad71e03b:9572a60a63ecf7dd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
  "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
  "pid": 690365,
  "sha256": "2ba624871577aaea609c57281a8c0c175c6a5df41b33f4e3b1da3b23bde7d746",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "cargo_pkg_name": "unicode_names2",
  "cargo_pkg_version": "1.3.0",
  "context_path": "/tmp/native-trace-686425-1783995514820/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-686425-1783995514820/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 690365,
  "ppid": 690173,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c",
    "/target/debug/build/unicode_names2-b44907ea69b5d510",
    "/target/debug/deps",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/lib64",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254630           254630       4f    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254680           254680       4f    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2546d0           2546d0       4f    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254720           254720       4f    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254770           254770       93    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254810           254810       93    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2548b0           2548b0       93    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254950           254950       93    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bc0           254bc0        5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bd0           254bd0        5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/263e90           263e90        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2703e0           2703e0        5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/270a70           270a70        9    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/27d6b0           27d6b0        5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286440           286440       71    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2864c0           2864c0       71    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286540           286540       71    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2865c0           2865c0       71    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28af00           28af00       d5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28afe0           28afe0       de    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b0c0           28b0c0       d5    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b1a0           28b1a0       de    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c600           29c600       42    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c650           29c650       12    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c670           29c670        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c680           29c680       13    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6a0           29c6a0       26    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6d0           29c6d0       26    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c700           29c700       26    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c730           29c730       26    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d0d0           29d0d0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d110           29d110        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d1f0           29d1f0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d280           29d280        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d360           29d360        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3b0           29d3b0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3c0           29d3c0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3e0           29d3e0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4c0           29d4c0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4d0           29d4d0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d510           29d510        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e520           29e520        d    16         /target/debug/deps",
    "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e540           29e540        d    16         /target/debug/deps"
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
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
      "kind": "object",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
      "directory": "/lib64",
      "kind": "dynamic_library",
      "path": "/lib64/ld-linux-x86-64.so.2",
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
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1",
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
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254630           254630       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254630           254630       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254680           254680       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254680           254680       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2546d0           2546d0       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2546d0           2546d0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254720           254720       4f    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254720           254720       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254770           254770       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254770           254770       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254810           254810       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254810           254810       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2548b0           2548b0       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2548b0           2548b0       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254950           254950       93    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254950           254950       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bc0           254bc0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bc0           254bc0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bd0           254bd0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bd0           254bd0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/263e90           263e90        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/263e90           263e90        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2703e0           2703e0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2703e0           2703e0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/270a70           270a70        9    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/270a70           270a70        9    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/27d6b0           27d6b0        5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/27d6b0           27d6b0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286440           286440       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286440           286440       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2864c0           2864c0       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2864c0           2864c0       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286540           286540       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286540           286540       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2865c0           2865c0       71    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2865c0           2865c0       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28af00           28af00       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28af00           28af00       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28afe0           28afe0       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28afe0           28afe0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b0c0           28b0c0       d5    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b0c0           28b0c0       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b1a0           28b1a0       de    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b1a0           28b1a0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c600           29c600       42    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c600           29c600       42    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c650           29c650       12    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c650           29c650       12    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c670           29c670        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c670           29c670        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c680           29c680       13    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c680           29c680       13    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6a0           29c6a0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6a0           29c6a0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6d0           29c6d0       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6d0           29c6d0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c700           29c700       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c700           29c700       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c730           29c730       26    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c730           29c730       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d0d0           29d0d0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d0d0           29d0d0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d110           29d110        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d110           29d110        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d1f0           29d1f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d1f0           29d1f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d280           29d280        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d280           29d280        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d360           29d360        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d360           29d360        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3b0           29d3b0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3b0           29d3b0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3c0           29d3c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3c0           29d3c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3e0           29d3e0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3e0           29d3e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4c0           29d4c0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4c0           29d4c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4d0           29d4d0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4d0           29d4d0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d510           29d510        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d510           29d510        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e520           29e520        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e520           29e520        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "dynamic_library",
      "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
      "source": "link_map"
    },
    {
      "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e540           29e540        d    16         /target/debug/deps",
      "kind": "dynamic_library",
      "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e540           29e540        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
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
  "map_path": "/tmp/native-trace-link-cc-690365-1783995585586588126.map",
  "pid": 690365,
  "ppid": 690173,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-690365-1783995585586588126.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
  "parse_error_count": 1,
  "parsed_event_count": 612,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 613,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "     690493 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n42.938  ps               690493 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n43.116  sh               690498 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n43.118  cpuUsage.sh      690498 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n43.120  sed              690499 690498   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n43.126  rustc            690497 689095   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"generator-timing\", \"no_std\", \"unstable\")) ...\n43.192  cat              690503 690498   0 /usr/bin/cat /proc/2240539/stat\n43.194  cat              690504 690498   0 /usr/bin/cat /proc/4193716/stat\n43.409  sleep            690505 690498   0 /usr/bin/sleep 1\n44.542  sed              690506 690498   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n44.598  cat              690507 690498   0 /usr/bin/cat /proc/2240539/stat\n44.600  cat              690509 690498   0 /usr/bin/cat /proc/4193716/stat\n45.497  runc             690524 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process3422426217 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n45.615  cc               690525 690497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/self-contained/cc -m64 /target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib /target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib /target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib ...\n45.685  cc               690531 690525   0 /usr/bin/cc -m64 /target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib /target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib /target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib ...\n45.693  exe              690534 690524   0 /proc/self/exe init\n45.716  collect2         690535 690531   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqFDSnV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n45.721  ld.lld           690536 690535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqFDSnV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510 ...\n45.725  rust-lld         690536 690535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqFDSnV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n45.774  curl             690538 690524   0 /usr/bin/curl -f http://localhost:9091/healthz\n46.296  aarch64-linux-g  690545 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n46.301  cc1plus          690546 690545   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/RemoveUnusedBrs.cpp ...\n46.453  aarch64-linux-g  690547 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n46.456  cc1plus          690548 690547   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n46.723  runc             690549 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1827532119 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n46.991  exe              690560 690549   0 /proc/self/exe init\n47.315  rustc            690588 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cranelift_codegen --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-codegen-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"gimli\" --cfg feature=\"std\" ...\n47.438  rustc            690586 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name addr2line --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/addr2line-0.19.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"compiler_builtins\", \"core\", \"cpp_demangle\", \"default\", \"fallible-iterator\", \"object\", \"rustc-deman -C metadata=12e05f21822c2394 ...\n47.731  sh               690596 2147557   0 /bin/sh -c which ps\n47.780  rustc            690598 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"alloc\" --cfg ...\n47.792  which            690596 2147557   0 /usr/bin/which ps\n47.793  etcdctl          690578 690549   0 /usr/local/bin/etcdctl endpoint health\n47.796  sh               690601 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n47.798  ps               690601 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n48.250  build-script-bu  690612 689095   0 /target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build\n48.427  rustc            690618 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cexpr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cexpr-0.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=49029af32681dec0 ...\n48.996  sh               690624 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n49.089  cpuUsage.sh      690624 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n49.090  sed              690630 690624   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n49.093  cat              690631 690624   0 /usr/bin/cat /proc/2240539/stat\n49.094  cat              690632 690624   0 /usr/bin/cat /proc/4193716/stat\n49.095  sleep            690633 690624   0 /usr/bin/sleep 1\n49.398  rustc            690651 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clang_sys --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clang_3_5\" --cfg feature=\"clang_3_6\" --cfg feature=\"clang_3_7\" ...\n49.410  as               690654 684581   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-StripEH.o /tmp/ccr38QhZ.s\n49.508  rustc            690660 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name axum --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/axum-0.8.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::verbose_file_reads --warn=clippy::unused_self --forbid=unsafe_code --warn=unreachable_pub --warn=clippy::unnested_or_patterns ...\n49.643  as               690666 670371   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/bd3f41d09f19c9b0-DuplicateFunctionElimination.o /tmp/cckQVF3v.s\n50.138  sed              690673 690624   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n50.138  cat              690674 690624   0 /usr/bin/cat /proc/2240539/stat\n50.138  cat              690676 690624   0 /usr/bin/cat /proc/4193716/stat\n50.222  as               690672 671636   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/bd3f41d09f19c9b0-Strip.o ...\n50.281  rustc            690684 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-1.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(hyper_unstable_tracing) --check-cfg cfg(hyper_unstable_ffi) --cfg ...\n50.285  as               690686 687871   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n50.616  rustc            690694 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_names2 --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"generator-timing\", \"no_std\", \"unstable\")) ...\n50.923  aarch64-linux-g  690702 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n50.960  cc1plus          690705 690702   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/InstrumentLocals.cpp ...\n51.030  aarch64-linux-g  690706 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n51.042  cc1plus          690707 690706   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n52.325  powerpc64le-lin  690720 626080   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I ...\n52.455  cc1plus          690723 690720   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n52.865  sh               690727 2147557   0 /bin/sh -c which ps\n52.867  which            690727 2147557   0 /usr/bin/which ps\n52.871  sh               690728 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n52.873  ps               690728 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n53.555  16               690733 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n53.683  frpc             690733 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n53.684  16               690734 1        0 /proc/self/fd/16 --deserialize 135 --log-level info --log-target journal-or-kmsg\n53.812  sa1              690734 1        0 /usr/lib64/sa/sa1 1 1\n53.812  sadc             690734 1        0 /usr/lib64/sa/sadc -F -L -S DISK 1 1 /var/log/sa\n54.144  sh               690742 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n54.146  cpuUsage.sh      690742 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n54.148  sed              690743 690742   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n54.153  cat              690744 690742   0 /usr/bin/cat /proc/2240539/stat\n54.339  cat              690745 690742   0 /usr/bin/cat /proc/4193716/stat\n54.518  sleep            690751 690742   0 /usr/bin/sleep 1\n55.138  rustc            690769 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name which --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/which-4.4.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"regex\")) -C metadata=22b284ddf9408e8b ...\n55.295  rustc            690781 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio_stream --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-stream-0.1.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"net\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"fs\", \"full\", \"io-util\", \"net\", \"signal\", \"sync\", \"time\", \"tokio-util\")) ...\n55.452  rustc            690779 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio_util --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-util-0.7.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(fuzzing) --check-cfg cfg(loom) --check-cfg ...\n55.519  sed              690788 690742   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n55.635  cat              690793 690742   0 /usr/bin/cat /proc/2240539/stat\n55.817  cat              690796 690742   0 /usr/bin/cat /proc/4193716/stat\n56.113  rustc            690802 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_jit_debug --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-jit-debug-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"gdb_jit_int\" --cfg feature=\"object\" --cfg feature=\"once_cell\" ...\n57.409  as               690821 642823   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/f7deeeb1a9f9c241-LocalGraph.o ...\n57.929  sh               690828 2147557   0 /bin/sh -c which ps\n58.016  which            690828 2147557   0 /usr/bin/which ps\n58.098  sh               690830 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n58.098  ps               690830 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n59.462  rustc            690843 689095   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_names2 --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"generator-timing\", \"no_std\", \"unstable\")) ...\n59.476  sh               690845 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n59.479  cpuUsage.sh      690845 2147557   0 \n59.482  sed              690846 690845   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n59.536  cat              690847 690845   0 /usr/bin/cat /proc/2240539/stat\n59.541  cat              690848 690845   0 /usr/bin/cat /proc/4193716/stat\n59.543  sleep            690849 690845   0 /usr/bin/sleep 1\n59.620  riscv64-linux-g  690850 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n59.620  cc1plus          690855 690850   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n59.842  as               690858 688944   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/bd3f41d09f19c9b0-Poppify.o /tmp/ccAWyT2U.s\n60.123  rustc            690863 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-1.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(hyper_unstable_tracing) --check-cfg cfg(hyper_unstable_ffi) --cfg ...\n60.545  sed              690878 690845   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n60.938  cat              690884 690845   0 /usr/bin/cat /proc/2240539/stat\n61.034  cat              690894 690845   0 /usr/bin/cat /proc/4193716/stat\n62.194  runc             690935 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2177839683 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n62.216  exe              690944 690935   0 /proc/self/exe init\n62.268  curl             690946 690935   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n62.432  rustc            690956 684688   0 \n62.609  rustc            690962 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tower --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tower-0.5.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"__common\" --cfg feature=\"balance\" --cfg feature=\"buffer\" ...\n62.741  powerpc64le-lin  690969 626080   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I ...\n62.896  cc1plus          690970 690969   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n63.058  sh               690972 2147557   0 /bin/sh -c which ps\n63.153  which            690972 2147557   0 /usr/bin/which ps\n63.279  sh               690975 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n63.280  ps               690975 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n63.623  rustc            690980 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper_util --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-util-0.1.14/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"client-legacy\" --cfg feature=\"default\" ...\n63.754  sh               690981 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n63.799  cpuUsage.sh      690981 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n64.058  sed              690986 690981   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n64.128  cat              690990 690981   0 /usr/bin/cat /proc/2240539/stat\n64.200  cat              690991 690981   0 \n64.201  sleep            690993 690981   0 /usr/bin/sleep 1\n64.332  as               690994 688279   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n64.455  aarch64-linux-g  690995 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n64.457  cc1plus          690996 690995   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/PickLoadSigns.cpp ...\n64.863  as               690999 641743   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/f7deeeb1a9f9c241-LocalGraph.o /tmp/ccFBiFNL.s\n65.186  rustc            691004 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"std\" --cfg ...\n65.203  sed              691006 690981   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n65.437  cat              691009 690981   0 /usr/bin/cat /proc/2240539/stat\n65.442  cat              691011 690981   0 /usr/bin/cat /proc/4193716/stat\n66.362  as               691037 690455   0 \n67.222  riscv64-linux-g  691082 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n67.226  cc1plus          691084 691082   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n67.226  riscv64-linux-g  691083 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n67.229  cc1plus          691085 691083   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n68.120  sh               691092 2147557   0 /bin/sh -c which ps\n68.318  which            691092 2147557   0 \n68.318  sh               691097 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n68.319  ps               691097 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n68.319  rustc            691096 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prettyplease --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) -C metadata=ec9e4f6e6a8d7b77 ...\n68.547  sh               691101 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n68.548  cpuUsage.sh      691101 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n68.551  sed              691102 691101   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n68.558  cat              691103 691101   0 /usr/bin/cat /proc/2240539/stat\n68.560  cat              691104 691101   0 /usr/bin/cat /proc/4193716/stat\n68.588  sleep            691105 691101   0 /usr/bin/sleep 1\n68.813  rustc            691113 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cranelift_frontend --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-frontend-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n68.886  rustc            691114 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cranelift_native --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-native-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n69.739  sed              691122 691101   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n69.810  cat              691123 691101   0 /usr/bin/cat /proc/2240539/stat\n69.812  cat              691125 691101   0 /usr/bin/cat /proc/4193716/stat\n70.154  as               691127 688750   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-Souperify.o /tmp/ccNnuo1d.s\n70.308  16               691132 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n70.335  frpc             691132 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n70.338  rustc            691133 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name axum --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/axum-0.8.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::verbose_file_reads --warn=clippy::unused_self --forbid=unsafe_code --warn=unreachable_pub --warn=clippy::unnested_or_patterns ...\n70.926  rustc            691150 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_cranelift_shared --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-cranelift-shared-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=17f846064b0ba56e ...\n71.055  rustc            691153 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cranelift_wasm --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-wasm-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n71.275  rustc            691169 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper_util --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-util-0.1.14/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"client-legacy\" --cfg feature=\"default\" ...\n71.772  cc1plus          691177 691176   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n71.772  aarch64-linux-g  691176 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n73.049  rustc            691197 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_types --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-types-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=b58645071cf370a2 ...\n73.829  rustc            691215 689485   0 \n73.924  sh               691214 2147557   0 /bin/sh -c which ps\n73.926  which            691214 2147557   0 /usr/bin/which ps\n73.929  sh               691218 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n73.932  ps               691218 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n74.344  as               691228 690445   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n74.515  sh               691231 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n74.580  cpuUsage.sh      691231 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n74.669  sed              691232 691231   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n74.744  runc             691235 671314   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca --log-format json --systemd-cgroup kill --all 98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca639bd 9\n74.760  cat              691242 691231   0 /usr/bin/cat /proc/2240539/stat\n74.834  rustc            691243 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper_timeout --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-timeout-0.5.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=5d1ff6c40b56becb ...\n74.843  cat              691247 691231   0 /usr/bin/cat /proc/4193716/stat\n74.845  sleep            691248 691231   0 /usr/bin/sleep 1\n75.562  runc             691263 671314   0 \n75.665  containerd-shim  691273 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca639bd -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca delete\n75.724  runc             691282 691273   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca639b --log-format json delete --force 98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca639bd\n75.825  rustc            691292 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tonic --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tonic-0.14.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --deny=clippy::uninlined_format_args --warn=rust_2018_idioms --warn=missing_docs --warn=missing_debug_implementations --deny=rustdoc::broken_intra_doc_links ...\n75.849  sed              691295 691231   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n75.856  cat              691296 691231   0 /usr/bin/cat /proc/2240539/stat\n75.859  cat              691298 691231   0 /usr/bin/cat /proc/4193716/stat\n76.195  aarch64-linux-g  691303 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n76.200  cc1plus          691304 691303   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n76.255  as               691305 684325   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n76.312  systemd-sysctl   691309 691308   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdfc3141 --prefix=/net/ipv4/neigh/vethdfc3141 --prefix=/net/ipv6/conf/vethdfc3141 --prefix=/net/ipv6/neigh/vethdfc3141\n76.442  cargo            691315 690424   0 \n76.553  riscv64-linux-g  691314 626155   0 /usr/sbin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n76.623  runc             691319 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1670223064 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n76.632  exe              691327 691319   0 /proc/self/exe init\n76.732  curl             691329 691319   0 /usr/bin/curl -f http://localhost:9091/healthz\n76.765  cc1plus          691335 691314   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n77.070  rustc            691340 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n78.059  rustup           691352 670543   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n78.631  sh               691367 2147557   0 /bin/sh -c which ps\n78.732  which            691367 2147557   0 /usr/bin/which ps\n79.122  sh               691377 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n79.125  ps               691377 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n79.161  rustc            691375 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) ...\n79.199  rustc            691379 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6cee1ea7c2ce8c63 ...\n79.201  rustc            691380 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0919eec9d4c8c0c2 ...\n79.207  rustc            691382 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) -C metadata=9631560503d11e13 ...\n79.207  rustc            691392 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n79.214  rustc            691394 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) ...\n79.370  rustc            691399 691315   0 /usr/local/sbin/rustc --crate-name minimal_lexical --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"compact\", \"default\", \"lint\", \"nightly\", \"std\")) ...\n79.370  rustc            691395 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"std\" --cfg ...\n79.371  rustc            691389 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n79.531  rustc            691400 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=cc8f9a7b2578854f ...\n"
}
```

#### Record 30

```json
{
  "argv": [
    "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 688783,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
  "pid": 688783,
  "ppid": 688502,
  "root_cargo_pid": 688502,
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
  "build_script_root_pid": 688783,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 688786,
  "ppid": 688783,
  "root_cargo_pid": 688502,
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
  "build_script_root_pid": 690428,
  "build_script_target_dir": "unicode_names2-b44907ea69b5d510",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
  "pid": 690428,
  "ppid": 688502,
  "root_cargo_pid": 688502,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
  "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "event_id": "bsrun:db5f63d2bfa7fb64:1a37a2067149b32e:a43ba5a7be190f37",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
  "out_dir": "/target/debug/build/unicode_names2-b44907ea69b5d510/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
  "success": true,
  "target": null,
  "version": "1.3.0",
  "_owner": {
    "crate": "unicode_names2",
    "version": "1.3.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
    "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
  "build_script_root_pid": 688783,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 688786,
  "ppid": 688783,
  "root_cargo_pid": 688502,
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
  "time": "2026-07-14T02:20:27.816907+00:00",
  "crate": "unicode_names2",
  "version": "1.3.0",
  "architecture": "riscv64",
  "duration_seconds": 133.40018695686013,
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
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "manifest_path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "workspace_root": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0"
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
          "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
          "name": "unicode_names2",
          "version": "1.3.0",
          "manifest_path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0"
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
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
      "pid": 688708,
      "ppid": 688561,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
      "event_id": "used:cc:b47364ada97c6bc2:7e3a41dcf0a59539:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
      "pid": 688708,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
      "pid": 688708,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
      "pid": 688708,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
      "pid": 688708,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
      "pid": 688708,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
      "context_path": "/tmp/native-trace-686425-1783995514820/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-686425-1783995514820/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 688708,
      "ppid": 688561,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/raw-dylibs",
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
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL",
        "/target/debug/build/libc-c3c858474dcfa7e6",
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
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcBuZMwL/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-688708-1783995558156278642.map",
      "pid": 688708,
      "ppid": 688561,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-688708-1783995558156278642.map"
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 690365,
      "ppid": 690173,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:d39869de7258019e:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
      "pid": 690365,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:ddb5541122ee3513:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "6c8f28bbb543a4de0fd24b4f714e14e13020f9a077cae4a2387242f2e8351f07",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:fc361c6b9238d5a5:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "862eb4261f6b79c74ea2452fc70b5ead0ed8f05ade85b0bfcee503a7b6cd51d3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:a0e8d701ee8fe006:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "2cbd08eab74e3371f88a174a55723469393a480500ad8d2900223d363981f19e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:2ab9838a77614eb3:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "250a9cbf054f76a0f94597ff792f8023573c1719b9b3ef9fe1e8b9b9c73460a6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:01b92da1903c09e2:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "a30e56818f153d1765f7344747c2e4ef99fbefef09b5f16a4bb94d19d3254714",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:a54bd33b7ff25dcd:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "8bcc8d9fa738d8b561857e094bd44f3c5f334168e24af012b412cbcac61fa871",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:1bf74e97bb58c9ec:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "82b1bf11e045c5a3ba27d7b435989950aabdabbde330b9eebb982cf0375d736e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:2ec006aa4ff0bafd:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "85ca4d23564d146b631e29091301ab134d96c92e66870947d4ac8b8840bb2b88",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:f36ba7d17d906d28:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "dc6423d1bc33a0cfae506729d075a53dd9d7921d1bec55acb86b12634d60f91b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:b16d78712e0ddda8:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "17c0839845ee8fbd95ed7c22cbc0cd5d8033f0355b5d677c981a9e40408a641b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:e7f2cf85bc8e0700:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "28419972c73e42d65c64bb3c03652af56685036cacbf23a12041be4284e30523",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "used:cc:94e6a9108277b074:5fad05daad71e03b:9572a60a63ecf7dd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510",
      "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
      "pid": 690365,
      "sha256": "2ba624871577aaea609c57281a8c0c175c6a5df41b33f4e3b1da3b23bde7d746",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "cargo_pkg_name": "unicode_names2",
      "cargo_pkg_version": "1.3.0",
      "context_path": "/tmp/native-trace-686425-1783995514820/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-686425-1783995514820/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 690365,
      "ppid": 690173,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c",
        "/target/debug/build/unicode_names2-b44907ea69b5d510",
        "/target/debug/deps",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu",
        "/lib64",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254630           254630       4f    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254680           254680       4f    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2546d0           2546d0       4f    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254720           254720       4f    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254770           254770       93    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254810           254810       93    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2548b0           2548b0       93    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254950           254950       93    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bc0           254bc0        5    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bd0           254bd0        5    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/263e90           263e90        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2703e0           2703e0        5    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/270a70           270a70        9    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/27d6b0           27d6b0        5    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286440           286440       71    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2864c0           2864c0       71    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286540           286540       71    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2865c0           2865c0       71    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28af00           28af00       d5    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28afe0           28afe0       de    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b0c0           28b0c0       d5    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b1a0           28b1a0       de    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c600           29c600       42    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c650           29c650       12    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c670           29c670        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c680           29c680       13    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6a0           29c6a0       26    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6d0           29c6d0       26    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c700           29c700       26    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c730           29c730       26    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d0d0           29d0d0        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d110           29d110        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d1f0           29d1f0        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d280           29d280        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d360           29d360        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3b0           29d3b0        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3c0           29d3c0        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3e0           29d3e0        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4c0           29d4c0        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4d0           29d4d0        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d510           29d510        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e520           29e520        d    16         /target/debug/deps",
        "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e540           29e540        d    16         /target/debug/deps"
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
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/rustcePpn4c/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.1bojgwr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.1bojgwr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.1bojgwr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.1bojgwr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.1bojgwr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.1bojgwr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.1bojgwr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.1bojgwr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.1bojgwr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.1bojgwr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.1bojgwr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicode_names2-b44907ea69b5d510",
          "kind": "object",
          "path": "/target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.1bojgwr.rcgu.o",
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
          "directory": "/lib64",
          "kind": "dynamic_library",
          "path": "/lib64/ld-linux-x86-64.so.2",
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
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1",
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
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254630           254630       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254630           254630       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h21bdb74c846bc970E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254680           254680       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254680           254680       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h34ba640b7618cf7cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2546d0           2546d0       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2546d0           2546d0       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h46a960fd059bd955E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254720           254720       4f    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254720           254720       4f    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$13with_capacity17h7f864763d94917e2E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254770           254770       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254770           254770       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h1c1eb10491ce4763E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254810           254810       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254810           254810       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h224551f8611f4419E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2548b0           2548b0       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2548b0           2548b0       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h42f195ca077b811eE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254950           254950       93    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254950           254950       93    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN5alloc5slice99_$LT$impl$u20$core..slice..sort..stable..BufGuard$LT$T$GT$$u20$for$u20$alloc..vec..Vec$LT$T$GT$$GT$19as_uninit_slice_mut17h630c112e87d40741E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bc0           254bc0        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bc0           254bc0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h037df019b9c64fcdE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bd0           254bd0        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/254bd0           254bd0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.00.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h84363b7da4c542f7E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/263e90           263e90        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/263e90           263e90        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.06.rcgu.o):(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h6e8b4309fa36eac7E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2703e0           2703e0        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2703e0           2703e0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h176b1de44711e967E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/270a70           270a70        9    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/270a70           270a70        9    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.07.rcgu.o):(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17he786dbea3c637c6fE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/27d6b0           27d6b0        5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/27d6b0           27d6b0        5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.03.rcgu.o):(.text._ZN68_$LT$T$u20$as$u20$core..slice..sort..stable..quicksort..IsFreeze$GT$9is_freeze17h9c1b1b464389ae0aE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286440           286440       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286440           286440       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h1efc2cc1d70f50afE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2864c0           2864c0       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2864c0           2864c0       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h248c57738197503cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286540           286540       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/286540           286540       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h7d719512046f0358E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2865c0           2865c0       71    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/2865c0           2865c0       71    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.02.rcgu.o):(.text._ZN99_$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17he24ff1af229509bbE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28af00           28af00       d5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28af00           28af00       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h56fd2b971ebad4e3E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28afe0           28afe0       de    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28afe0           28afe0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17h6fc75b412148e952E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b0c0           28b0c0       d5    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b0c0           28b0c0       d5    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hecfc320180cd3838E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b1a0           28b1a0       de    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/28b1a0           28b1a0       de    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.09.rcgu.o):(.text._ZN95_$LT$core..slice..sort..stable..merge..MergeState$LT$T$GT$$u20$as$u20$core..ops..drop..Drop$GT$4drop17hed79e12bf7397d12E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c600           29c600       42    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c600           29c600       42    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h1b9a3a2a49258872E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c650           29c650       12    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c650           29c650       12    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h72ec125c9a349711E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c670           29c670        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c670           29c670        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hd1e6c5a1fe712ccbE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c680           29c680       13    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c680           29c680       13    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hea1268c6b26d1addE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6a0           29c6a0       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6a0           29c6a0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h192f9a67eef50b7eE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6d0           29c6d0       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c6d0           29c6d0       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17h4b0538e13f590fd0E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c700           29c700       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c700           29c700       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hbb55a6b487f4d6eeE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c730           29c730       26    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29c730           29c730       26    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN103_$LT$core..iter..sources..repeat..Repeat$LT$A$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$9size_hint17hf8f7cbf23ed2944cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d0d0           29d0d0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d0d0           29d0d0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr113drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h51b0e9b02ae04263E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d110           29d110        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d110           29d110        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr117drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$phf_generator..try_generate_hash..Bucket$GT$$GT$17h8f783fa3e3287035E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d1f0           29d1f0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d1f0           29d1f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr122drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h543d629a35a3a779E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d280           29d280        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d280           29d280        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr126drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$u8$GT$$C$usize$RP$$GT$$GT$17h89afa1091f137fc6E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d350           29d350        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr162drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0759c5bd84ba0280E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d360           29d360        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d360           29d360        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr166drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$usize$C$alloc..vec..Vec$LT$$LP$unicode_names2_generator..phf..Hash$C$char$RP$$GT$$RP$$GT$$GT$17h0cc1bdb66b7acf86E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3b0           29d3b0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3b0           29d3b0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hc5d2c76eac07b62aE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3c0           29d3c0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3c0           29d3c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr186drop_in_place$LT$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h9940860d055404fcE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3e0           29d3e0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d3e0           29d3e0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr188drop_in_place$LT$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h1416b85b3e502b78E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d420           29d420        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr214drop_in_place$LT$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h948848cdf87c416cE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4c0           29d4c0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4c0           29d4c0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u32$C$alloc..vec..Vec$LT$u32$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u32$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hb271bcc28fb426dfE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4d0           29d4d0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4d0           29d4d0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr348drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$u64$C$alloc..vec..Vec$LT$u64$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$u64$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17hd546089da0896a52E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d4f0           29d4f0        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr351drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$char$C$alloc..vec..Vec$LT$char$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$char$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h57212855628b3c6bE",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d510           29d510        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29d510           29d510        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr390drop_in_place$LT$$LT$core..iter..adapters..take..Take$LT$I$GT$$u20$as$u20$core..iter..adapters..take..SpecTake$GT$..spec_for_each..check$LT$$LP$u32$C$u32$RP$$C$alloc..vec..Vec$LT$$LP$u32$C$u32$RP$$GT$..extend_trusted$LT$core..iter..adapters..take..Take$LT$core..iter..sources..repeat..Repeat$LT$$LP$u32$C$u32$RP$$GT$$GT$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$17h83edfaf03f4b1fa2E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e520           29e520        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e520           29e520        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "dynamic_library",
          "path": "/target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr95drop_in_place$LT$core..slice..sort..stable..merge..MergeState$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17h7a6412371b5f3855E",
          "source": "link_map"
        },
        {
          "directory": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e540           29e540        d    16         /target/debug/deps",
          "kind": "dynamic_library",
          "path": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0/29e540           29e540        d    16         /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib(unicode_names2_generator-293e64d322c98040.unicode_names2_generator.d31f13cadc5eda26-cgu.15.rcgu.o):(.text._ZN4core3ptr99drop_in_place$LT$core..slice..sort..shared..smallsort..CopyOnDrop$LT$$LP$char$C$$RF$str$RP$$GT$$GT$17hb1d3405eb61fd2f0E",
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
      "map_path": "/tmp/native-trace-link-cc-690365-1783995585586588126.map",
      "pid": 690365,
      "ppid": 690173,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-690365-1783995585586588126.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
      "parsed_event_count": 612,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 613,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "     690493 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n42.938  ps               690493 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n43.116  sh               690498 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n43.118  cpuUsage.sh      690498 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n43.120  sed              690499 690498   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n43.126  rustc            690497 689095   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"generator-timing\", \"no_std\", \"unstable\")) ...\n43.192  cat              690503 690498   0 /usr/bin/cat /proc/2240539/stat\n43.194  cat              690504 690498   0 /usr/bin/cat /proc/4193716/stat\n43.409  sleep            690505 690498   0 /usr/bin/sleep 1\n44.542  sed              690506 690498   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n44.598  cat              690507 690498   0 /usr/bin/cat /proc/2240539/stat\n44.600  cat              690509 690498   0 /usr/bin/cat /proc/4193716/stat\n45.497  runc             690524 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process3422426217 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n45.615  cc               690525 690497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/self-contained/cc -m64 /target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib /target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib /target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib ...\n45.685  cc               690531 690525   0 /usr/bin/cc -m64 /target/debug/build/unicode_names2-b44907ea69b5d510/rustc3rhJru/symbols.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.09uy9d4xb2gee2awfcb8bc4nw.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.2qtwykky4vrui5c6r8loecqfd.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4fom4lmk75ar5shnlseqb5d37.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.4o0um2d5qmq9vzne9qt8f9kqh.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.73d34sgow3ht4y91do4feouel.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.88grp4j7ll9p1yni915rze6p4.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.d5764j8q0hhn3m0mw7zll65sl.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dpyziayo9t4twzttzvumg9j6a.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.dt66x7rjph8mma3js9slbvs0g.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e024pnv19irqun4zgbo72s7tr.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.e9vqdooou2a93mn1wfa9wrfxt.010jggg.rcgu.o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510.0y8s9i9g8pdf3p3oeckxdr5gl.010jggg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libunicode_names2_generator-293e64d322c98040.rlib /target/debug/deps/libphf_codegen-2be8357290ad31b2.rlib /target/debug/deps/libphf_generator-7cb5e263f4be7c1f.rlib ...\n45.693  exe              690534 690524   0 /proc/self/exe init\n45.716  collect2         690535 690531   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqFDSnV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n45.721  ld.lld           690536 690535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqFDSnV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/unicode_names2-b44907ea69b5d510/build_script_build-b44907ea69b5d510 ...\n45.725  rust-lld         690536 690535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqFDSnV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n45.774  curl             690538 690524   0 /usr/bin/curl -f http://localhost:9091/healthz\n46.296  aarch64-linux-g  690545 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n46.301  cc1plus          690546 690545   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/RemoveUnusedBrs.cpp ...\n46.453  aarch64-linux-g  690547 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n46.456  cc1plus          690548 690547   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n46.723  runc             690549 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1827532119 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n46.991  exe              690560 690549   0 /proc/self/exe init\n47.315  rustc            690588 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cranelift_codegen --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-codegen-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"gimli\" --cfg feature=\"std\" ...\n47.438  rustc            690586 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name addr2line --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/addr2line-0.19.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"compiler_builtins\", \"core\", \"cpp_demangle\", \"default\", \"fallible-iterator\", \"object\", \"rustc-deman -C metadata=12e05f21822c2394 ...\n47.731  sh               690596 2147557   0 /bin/sh -c which ps\n47.780  rustc            690598 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"alloc\" --cfg ...\n47.792  which            690596 2147557   0 /usr/bin/which ps\n47.793  etcdctl          690578 690549   0 /usr/local/bin/etcdctl endpoint health\n47.796  sh               690601 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n47.798  ps               690601 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n48.250  build-script-bu  690612 689095   0 /target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build\n48.427  rustc            690618 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cexpr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cexpr-0.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=49029af32681dec0 ...\n48.996  sh               690624 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n49.089  cpuUsage.sh      690624 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n49.090  sed              690630 690624   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n49.093  cat              690631 690624   0 /usr/bin/cat /proc/2240539/stat\n49.094  cat              690632 690624   0 /usr/bin/cat /proc/4193716/stat\n49.095  sleep            690633 690624   0 /usr/bin/sleep 1\n49.398  rustc            690651 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clang_sys --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clang_3_5\" --cfg feature=\"clang_3_6\" --cfg feature=\"clang_3_7\" ...\n49.410  as               690654 684581   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-StripEH.o /tmp/ccr38QhZ.s\n49.508  rustc            690660 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name axum --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/axum-0.8.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::verbose_file_reads --warn=clippy::unused_self --forbid=unsafe_code --warn=unreachable_pub --warn=clippy::unnested_or_patterns ...\n49.643  as               690666 670371   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/bd3f41d09f19c9b0-DuplicateFunctionElimination.o /tmp/cckQVF3v.s\n50.138  sed              690673 690624   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n50.138  cat              690674 690624   0 /usr/bin/cat /proc/2240539/stat\n50.138  cat              690676 690624   0 /usr/bin/cat /proc/4193716/stat\n50.222  as               690672 671636   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/bd3f41d09f19c9b0-Strip.o ...\n50.281  rustc            690684 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-1.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(hyper_unstable_tracing) --check-cfg cfg(hyper_unstable_ffi) --cfg ...\n50.285  as               690686 687871   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n50.616  rustc            690694 688502   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_names2 --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"generator-timing\", \"no_std\", \"unstable\")) ...\n50.923  aarch64-linux-g  690702 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n50.960  cc1plus          690705 690702   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/InstrumentLocals.cpp ...\n51.030  aarch64-linux-g  690706 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n51.042  cc1plus          690707 690706   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n52.325  powerpc64le-lin  690720 626080   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I ...\n52.455  cc1plus          690723 690720   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n52.865  sh               690727 2147557   0 /bin/sh -c which ps\n52.867  which            690727 2147557   0 /usr/bin/which ps\n52.871  sh               690728 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n52.873  ps               690728 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n53.555  16               690733 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n53.683  frpc             690733 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n53.684  16               690734 1        0 /proc/self/fd/16 --deserialize 135 --log-level info --log-target journal-or-kmsg\n53.812  sa1              690734 1        0 /usr/lib64/sa/sa1 1 1\n53.812  sadc             690734 1        0 /usr/lib64/sa/sadc -F -L -S DISK 1 1 /var/log/sa\n54.144  sh               690742 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n54.146  cpuUsage.sh      690742 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n54.148  sed              690743 690742   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n54.153  cat              690744 690742   0 /usr/bin/cat /proc/2240539/stat\n54.339  cat              690745 690742   0 /usr/bin/cat /proc/4193716/stat\n54.518  sleep            690751 690742   0 /usr/bin/sleep 1\n55.138  rustc            690769 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name which --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/which-4.4.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"regex\")) -C metadata=22b284ddf9408e8b ...\n55.295  rustc            690781 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio_stream --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-stream-0.1.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"net\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"fs\", \"full\", \"io-util\", \"net\", \"signal\", \"sync\", \"time\", \"tokio-util\")) ...\n55.452  rustc            690779 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tokio_util --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tokio-util-0.7.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(fuzzing) --check-cfg cfg(loom) --check-cfg ...\n55.519  sed              690788 690742   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n55.635  cat              690793 690742   0 /usr/bin/cat /proc/2240539/stat\n55.817  cat              690796 690742   0 /usr/bin/cat /proc/4193716/stat\n56.113  rustc            690802 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_jit_debug --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-jit-debug-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"gdb_jit_int\" --cfg feature=\"object\" --cfg feature=\"once_cell\" ...\n57.409  as               690821 642823   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/f7deeeb1a9f9c241-LocalGraph.o ...\n57.929  sh               690828 2147557   0 /bin/sh -c which ps\n58.016  which            690828 2147557   0 /usr/bin/which ps\n58.098  sh               690830 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n58.098  ps               690830 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n59.462  rustc            690843 689095   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_names2 --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"generator-timing\", \"no_std\", \"unstable\")) ...\n59.476  sh               690845 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n59.479  cpuUsage.sh      690845 2147557   0 \n59.482  sed              690846 690845   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n59.536  cat              690847 690845   0 /usr/bin/cat /proc/2240539/stat\n59.541  cat              690848 690845   0 /usr/bin/cat /proc/4193716/stat\n59.543  sleep            690849 690845   0 /usr/bin/sleep 1\n59.620  riscv64-linux-g  690850 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n59.620  cc1plus          690855 690850   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n59.842  as               690858 688944   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/bd3f41d09f19c9b0-Poppify.o /tmp/ccAWyT2U.s\n60.123  rustc            690863 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-1.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(hyper_unstable_tracing) --check-cfg cfg(hyper_unstable_ffi) --cfg ...\n60.545  sed              690878 690845   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n60.938  cat              690884 690845   0 /usr/bin/cat /proc/2240539/stat\n61.034  cat              690894 690845   0 /usr/bin/cat /proc/4193716/stat\n62.194  runc             690935 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2177839683 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n62.216  exe              690944 690935   0 /proc/self/exe init\n62.268  curl             690946 690935   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n62.432  rustc            690956 684688   0 \n62.609  rustc            690962 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tower --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tower-0.5.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"__common\" --cfg feature=\"balance\" --cfg feature=\"buffer\" ...\n62.741  powerpc64le-lin  690969 626080   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I ...\n62.896  cc1plus          690970 690969   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n63.058  sh               690972 2147557   0 /bin/sh -c which ps\n63.153  which            690972 2147557   0 /usr/bin/which ps\n63.279  sh               690975 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n63.280  ps               690975 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n63.623  rustc            690980 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper_util --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-util-0.1.14/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"client-legacy\" --cfg feature=\"default\" ...\n63.754  sh               690981 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n63.799  cpuUsage.sh      690981 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n64.058  sed              690986 690981   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n64.128  cat              690990 690981   0 /usr/bin/cat /proc/2240539/stat\n64.200  cat              690991 690981   0 \n64.201  sleep            690993 690981   0 /usr/bin/sleep 1\n64.332  as               690994 688279   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n64.455  aarch64-linux-g  690995 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n64.457  cc1plus          690996 690995   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/PickLoadSigns.cpp ...\n64.863  as               690999 641743   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/f7deeeb1a9f9c241-LocalGraph.o /tmp/ccFBiFNL.s\n65.186  rustc            691004 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"std\" --cfg ...\n65.203  sed              691006 690981   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n65.437  cat              691009 690981   0 /usr/bin/cat /proc/2240539/stat\n65.442  cat              691011 690981   0 /usr/bin/cat /proc/4193716/stat\n66.362  as               691037 690455   0 \n67.222  riscv64-linux-g  691082 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n67.226  cc1plus          691084 691082   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n67.226  riscv64-linux-g  691083 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n67.229  cc1plus          691085 691083   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n68.120  sh               691092 2147557   0 /bin/sh -c which ps\n68.318  which            691092 2147557   0 \n68.318  sh               691097 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n68.319  ps               691097 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n68.319  rustc            691096 689485   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prettyplease --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) -C metadata=ec9e4f6e6a8d7b77 ...\n68.547  sh               691101 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n68.548  cpuUsage.sh      691101 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n68.551  sed              691102 691101   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n68.558  cat              691103 691101   0 /usr/bin/cat /proc/2240539/stat\n68.560  cat              691104 691101   0 /usr/bin/cat /proc/4193716/stat\n68.588  sleep            691105 691101   0 /usr/bin/sleep 1\n68.813  rustc            691113 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cranelift_frontend --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-frontend-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n68.886  rustc            691114 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cranelift_native --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-native-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n69.739  sed              691122 691101   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n69.810  cat              691123 691101   0 /usr/bin/cat /proc/2240539/stat\n69.812  cat              691125 691101   0 /usr/bin/cat /proc/4193716/stat\n70.154  as               691127 688750   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-Souperify.o /tmp/ccNnuo1d.s\n70.308  16               691132 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n70.335  frpc             691132 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n70.338  rustc            691133 684688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name axum --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/axum-0.8.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::verbose_file_reads --warn=clippy::unused_self --forbid=unsafe_code --warn=unreachable_pub --warn=clippy::unnested_or_patterns ...\n70.926  rustc            691150 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_cranelift_shared --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-cranelift-shared-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=17f846064b0ba56e ...\n71.055  rustc            691153 672464   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cranelift_wasm --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cranelift-wasm-0.95.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n71.275  rustc            691169 683337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper_util --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-util-0.1.14/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"client-legacy\" --cfg feature=\"default\" ...\n71.772  cc1plus          691177 691176   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n71.772  aarch64-linux-g  691176 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n73.049  rustc            691197 671759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasmtime_types --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasmtime-types-8.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=b58645071cf370a2 ...\n73.829  rustc            691215 689485   0 \n73.924  sh               691214 2147557   0 /bin/sh -c which ps\n73.926  which            691214 2147557   0 /usr/bin/which ps\n73.929  sh               691218 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n73.932  ps               691218 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n74.344  as               691228 690445   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n74.515  sh               691231 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n74.580  cpuUsage.sh      691231 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n74.669  sed              691232 691231   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n74.744  runc             691235 671314   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca --log-format json --systemd-cgroup kill --all 98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca639bd 9\n74.760  cat              691242 691231   0 /usr/bin/cat /proc/2240539/stat\n74.834  rustc            691243 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hyper_timeout --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hyper-timeout-0.5.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=5d1ff6c40b56becb ...\n74.843  cat              691247 691231   0 /usr/bin/cat /proc/4193716/stat\n74.845  sleep            691248 691231   0 /usr/bin/sleep 1\n75.562  runc             691263 671314   0 \n75.665  containerd-shim  691273 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca639bd -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca delete\n75.724  runc             691282 691273   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca639b --log-format json delete --force 98daef435adcd60b9df101791a769b5825d03d537c88fabf38ec2c8b2ca639bd\n75.825  rustc            691292 677677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tonic --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tonic-0.14.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --deny=clippy::uninlined_format_args --warn=rust_2018_idioms --warn=missing_docs --warn=missing_debug_implementations --deny=rustdoc::broken_intra_doc_links ...\n75.849  sed              691295 691231   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n75.856  cat              691296 691231   0 /usr/bin/cat /proc/2240539/stat\n75.859  cat              691298 691231   0 /usr/bin/cat /proc/4193716/stat\n76.195  aarch64-linux-g  691303 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n76.200  cc1plus          691304 691303   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n76.255  as               691305 684325   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n76.312  systemd-sysctl   691309 691308   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdfc3141 --prefix=/net/ipv4/neigh/vethdfc3141 --prefix=/net/ipv6/conf/vethdfc3141 --prefix=/net/ipv6/neigh/vethdfc3141\n76.442  cargo            691315 690424   0 \n76.553  riscv64-linux-g  691314 626155   0 /usr/sbin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n76.623  runc             691319 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1670223064 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n76.632  exe              691327 691319   0 /proc/self/exe init\n76.732  curl             691329 691319   0 /usr/bin/curl -f http://localhost:9091/healthz\n76.765  cc1plus          691335 691314   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n77.070  rustc            691340 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n78.059  rustup           691352 670543   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n78.631  sh               691367 2147557   0 /bin/sh -c which ps\n78.732  which            691367 2147557   0 /usr/bin/which ps\n79.122  sh               691377 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n79.125  ps               691377 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n79.161  rustc            691375 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) ...\n79.199  rustc            691379 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6cee1ea7c2ce8c63 ...\n79.201  rustc            691380 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0919eec9d4c8c0c2 ...\n79.207  rustc            691382 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) -C metadata=9631560503d11e13 ...\n79.207  rustc            691392 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n79.214  rustc            691394 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) ...\n79.370  rustc            691399 691315   0 /usr/local/sbin/rustc --crate-name minimal_lexical --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"compact\", \"default\", \"lint\", \"nightly\", \"std\")) ...\n79.370  rustc            691395 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"std\" --cfg ...\n79.371  rustc            691389 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n79.531  rustc            691400 691315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=cc8f9a7b2578854f ...\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 688783,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
      "pid": 688783,
      "ppid": 688502,
      "root_cargo_pid": 688502,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 688783,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 688786,
      "ppid": 688783,
      "root_cargo_pid": 688502,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 690428,
      "build_script_target_dir": "unicode_names2-b44907ea69b5d510",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
      "pid": 690428,
      "ppid": 688502,
      "root_cargo_pid": 688502,
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
      "cwd": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "event_id": "bsrun:db5f63d2bfa7fb64:1a37a2067149b32e:a43ba5a7be190f37",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/unicode_names2-b44907ea69b5d510/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
      "out_dir": "/target/debug/build/unicode_names2-b44907ea69b5d510/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
      "success": true,
      "target": null,
      "version": "1.3.0",
      "_owner": {
        "crate": "unicode_names2",
        "version": "1.3.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0#unicode_names2@1.3.0",
        "manifest_dir": "/tmp/crate-build-riscv64-37bp5wyo/src/unicode_names2-1.3.0",
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
      "build_script_root_pid": 688783,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 688786,
      "ppid": 688783,
      "root_cargo_pid": 688502,
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
