# `file-lock` `2.1.10`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 814330

Build-script executable: `/target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e`

Working directory: `/tmp/crate-build-aarch64-0ql4_hox/src/file-lock-2.1.10`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/libfile_lock.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-0ql4_hox/src/file-lock-2.1.10`

### Source directories

* `/tmp/crate-build-aarch64-0ql4_hox/src/file-lock-2.1.10/src`

### Source file examples

* `/tmp/crate-build-aarch64-0ql4_hox/src/file-lock-2.1.10/src/file_lock.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-0ql4_hox/src/file-lock-2.1.10`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/ea708c7824d36062-file_lock.o -c src/file_lock.c
```

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
