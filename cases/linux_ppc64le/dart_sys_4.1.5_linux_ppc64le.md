# `dart-sys` `4.1.5`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 839141

Build-script executable: `/target/debug/build/dart-sys-f05a7882a0a8a47a/build_script_build-f05a7882a0a8a47a`

Working directory: `/tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/dart-sys-ca281e5e289bfbbd/out/libdart_api_dl.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5`

### Source directories

* `/tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5/dart-sdk/include`

### Source file examples

* `/tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5/dart-sdk/include/dart_api_dl.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5/dart-sdk/include -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/dart-sys-ca281e5e289bfbbd/out/248f927bf32daba4-dart_api_dl.o -c /tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5/dart-sdk/include/dart_api_dl.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
