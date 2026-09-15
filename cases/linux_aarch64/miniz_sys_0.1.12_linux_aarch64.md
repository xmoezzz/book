# `miniz-sys` `0.1.12`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 990681

Build-script executable: `/target/debug/build/miniz-sys-a1520be8e078b97f/build_script_build-a1520be8e078b97f`

Working directory: `/tmp/crate-build-aarch64-pob8e6qf/src/miniz-sys-0.1.12`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/miniz-sys-6cfd2adf1e59fccd/out/libminiz.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-pob8e6qf/src/miniz-sys-0.1.12`

### Source directories

* `/tmp/crate-build-aarch64-pob8e6qf/src/miniz-sys-0.1.12`

### Source file examples

* `/tmp/crate-build-aarch64-pob8e6qf/src/miniz-sys-0.1.12/miniz.c`

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu -D MINIZ_NO_STDIO -D MINIZ_NO_ARCHIVE_APIS -D MINIZ_NO_ARCHIVE_WRITING_APIS -D MINIZ_NO_TIME -D MINIZ_NO_ZLIB_COMPATIBLE_NAMES <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
