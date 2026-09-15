# `miniz-sys` `0.1.12`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 990861

Build-script executable: `/target/debug/build/miniz-sys-a1520be8e078b97f/build_script_build-a1520be8e078b97f`

Working directory: `/tmp/crate-build-ppc64le-wh27ww57/src/miniz-sys-0.1.12`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/miniz-sys-a04854fe6813b1a1/out/libminiz.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-wh27ww57/src/miniz-sys-0.1.12`

### Source directories

* `/tmp/crate-build-ppc64le-wh27ww57/src/miniz-sys-0.1.12`

### Source file examples

* `/tmp/crate-build-ppc64le-wh27ww57/src/miniz-sys-0.1.12/miniz.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-wh27ww57/src/miniz-sys-0.1.12`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -w -fvisibility=hidden -DMINIZ_NO_STDIO -DMINIZ_NO_ARCHIVE_APIS -DMINIZ_NO_ARCHIVE_WRITING_APIS -DMINIZ_NO_TIME -DMINIZ_NO_ZLIB_COMPATIBLE_NAMES -o /target/powerpc64le-unknown-linux-gnu/debug/build/miniz-sys-a04854fe6813b1a1/out/db3b6bfb95261072-miniz.o -c miniz.c ...
```

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu -D MINIZ_NO_STDIO -D MINIZ_NO_ARCHIVE_APIS -D MINIZ_NO_ARCHIVE_WRITING_APIS -D MINIZ_NO_TIME -D MINIZ_NO_ZLIB_COMPATIBLE_NAMES <source> -msecure-plt -quiet -dumpbase <source> -m64 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
