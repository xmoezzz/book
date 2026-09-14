# `dart-sys` `4.1.5`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 839184

Build-script executable: `/target/debug/build/dart-sys-f05a7882a0a8a47a/build_script_build-f05a7882a0a8a47a`

Working directory: `/tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/dart-sys-c5f79a256687a864/out/libdart_api_dl.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5`

### Source directories

* `/tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5/dart-sdk/include`

### Source file examples

* `/tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5/dart-sdk/include/dart_api_dl.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5/dart-sdk/include -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/dart-sys-c5f79a256687a864/out/248f927bf32daba4-dart_api_dl.o -c /tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5/dart-sdk/include/dart_api_dl.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
