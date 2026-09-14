# `link-cplusplus` `1.0.9`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 224858

Build-script executable: `/target/debug/build/link-cplusplus-6425001543295aaf/build_script_build-6425001543295aaf`

Working directory: `/tmp/crate-build-aarch64-7usofa50/src/link-cplusplus-1.0.9`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/aarch64-unknown-linux-gnu/debug/build/link-cplusplus-a5d8ff51e518fad5/out/liblink-cplusplus.a`

### Source origin

* matches Linux x86_64 source path `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out/dummy.cc`, under build output directory `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out`

### Source directories

* `/target/aarch64-unknown-linux-gnu/debug/build/link-cplusplus-a5d8ff51e518fad5/out`

### Source file examples

* `/target/aarch64-unknown-linux-gnu/debug/build/link-cplusplus-a5d8ff51e518fad5/out/dummy.cc`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-7usofa50/src/link-cplusplus-1.0.9`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/link-cplusplus-a5d8ff51e518fad5/out/6fc10ba59c243478-dummy.o -c /target/aarch64-unknown-linux-gnu/debug/build/link-cplusplus-a5d8ff51e518fad5/out/dummy.cc
```

### Compilation

```text
cc1plus -quiet -imultiarch aarch64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
