# `file-lock` `2.1.10`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 816010

Build-script executable: `/target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e`

Working directory: `/tmp/crate-build-ppc64le-e_efncmo/src/file-lock-2.1.10`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/libfile_lock.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-e_efncmo/src/file-lock-2.1.10`

### Source directories

* `/tmp/crate-build-ppc64le-e_efncmo/src/file-lock-2.1.10/src`

### Source file examples

* `/tmp/crate-build-ppc64le-e_efncmo/src/file-lock-2.1.10/src/file_lock.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-e_efncmo/src/file-lock-2.1.10`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/ea708c7824d36062-file_lock.o -c src/file_lock.c
```

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
