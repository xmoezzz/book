# `libmimalloc-sys` `0.1.44`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 363383

Build-script executable: `/target/debug/build/libmimalloc-sys-f4207166b664f667/build_script_build-f4207166b664f667`

Working directory: `/tmp/crate-build-ppc64le-_qjqxzyy/src/libmimalloc-sys-0.1.44`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/libmimalloc-sys-8ca74cb6f5a037b9/out/libmimalloc.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-_qjqxzyy/src/libmimalloc-sys-0.1.44`

### Source directories

* `/tmp/crate-build-ppc64le-_qjqxzyy/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src`

### Source file examples

* `/tmp/crate-build-ppc64le-_qjqxzyy/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src/static.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch powerpc64le-linux-gnu -D MI_DEBUG=0 <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -gdwarf-4 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
