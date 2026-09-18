# `ittapi-sys` `0.4.0`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/ittapi-sys-d8e93a1c07f48bf8/out/libittnotify.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-_fgjntse/src/ittapi-sys-0.4.0`

### Source directories

* `/tmp/crate-build-riscv64-_fgjntse/src/ittapi-sys-0.4.0/c-library/src/ittnotify`

### Source file examples

* `/tmp/crate-build-riscv64-_fgjntse/src/ittapi-sys-0.4.0/c-library/src/ittnotify/ittnotify_static.c`
* `/tmp/crate-build-riscv64-_fgjntse/src/ittapi-sys-0.4.0/c-library/src/ittnotify/jitprofiling.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ittapi-sys-d8e93a1c07f48bf8/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
