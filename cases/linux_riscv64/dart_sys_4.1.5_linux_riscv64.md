# `dart-sys` `4.1.5`

Platform: Linux riscv64

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
