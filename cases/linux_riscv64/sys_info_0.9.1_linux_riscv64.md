# `sys-info` `0.9.1`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/sys-info-13b8bdd4f9a823ed/out/libinfo.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-zxe18_5n/src/sys-info-0.9.1`

### Source directories

* `/tmp/crate-build-riscv64-zxe18_5n/src/sys-info-0.9.1/c`

### Source file examples

* `/tmp/crate-build-riscv64-zxe18_5n/src/sys-info-0.9.1/c/linux.c`

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/sys-info-13b8bdd4f9a823ed/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
