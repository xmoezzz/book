# `c-kzg` `1.0.3`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/c-kzg-5d17959e8d535f25/out/libckzg.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3`

### Source directories

* `/tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3/src`

### Source file examples

* `/tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3/src/c_kzg_4844.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/c-kzg-5d17959e8d535f25/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
