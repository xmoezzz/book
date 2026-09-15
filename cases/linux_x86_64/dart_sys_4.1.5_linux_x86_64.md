# `dart-sys` `4.1.5`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 2071827

Build-script executable: `/work/target/debug/build/dart-sys-5c9adb7c54b9c4da/build_script_build-5c9adb7c54b9c4da`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/dart-sys-29e368b3f2834dd6/out/libdart_api_dl.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/dart-sdk/include`

### Source file examples

* `/work/dart-sdk/include/dart_api_dl.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /work/dart-sdk/include -Wall -Wextra -o /work/target/debug/build/dart-sys-29e368b3f2834dd6/out/248f927bf32daba4-dart_api_dl.o -c /work/dart-sdk/include/dart_api_dl.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/dart-sdk/include -imultiarch x86_64-linux-gnu /work/dart-sdk/include/dart_api_dl.c -quiet -dumpdir /work/target/debug/build/dart-sys-29e368b3f2834dd6/out/ -dumpbase 248f927bf32daba4-dart_api_dl.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
