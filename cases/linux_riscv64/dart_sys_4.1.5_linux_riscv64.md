# `dart-sys` `4.1.5`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 839278

Build-script executable: `/target/debug/build/dart-sys-f05a7882a0a8a47a/build_script_build-f05a7882a0a8a47a`

Working directory: `/tmp/crate-build-riscv64-2mnp1bgf/src/dart-sys-4.1.5`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/dart-sys-ffff3f34a86705f1/out/libdart_api_dl.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-2mnp1bgf/src/dart-sys-4.1.5`

### Source directories

* `/tmp/crate-build-riscv64-2mnp1bgf/src/dart-sys-4.1.5/dart-sdk/include`

### Source file examples

* `/tmp/crate-build-riscv64-2mnp1bgf/src/dart-sys-4.1.5/dart-sdk/include/dart_api_dl.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-2mnp1bgf/src/dart-sys-4.1.5`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /tmp/crate-build-riscv64-2mnp1bgf/src/dart-sys-4.1.5/dart-sdk/include -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/dart-sys-ffff3f34a86705f1/out/248f927bf32daba4-dart_api_dl.o -c /tmp/crate-build-riscv64-2mnp1bgf/src/dart-sys-4.1.5/dart-sdk/include/dart_api_dl.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/dart-sys-ffff3f34a86705f1/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
