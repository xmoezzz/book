# `file-lock` `2.1.10`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/libfile_lock.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-l4889u_u/src/file-lock-2.1.10`

### Source directories

* `/tmp/crate-build-riscv64-l4889u_u/src/file-lock-2.1.10/src`

### Source file examples

* `/tmp/crate-build-riscv64-l4889u_u/src/file-lock-2.1.10/src/file_lock.c`

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
