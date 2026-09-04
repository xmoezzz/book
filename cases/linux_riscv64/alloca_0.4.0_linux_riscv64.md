# `alloca` `0.4.0`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/alloca-035daa7e144f7c43/out/libcalloca.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-oa_sof97/src/alloca-0.4.0`

### Source directories

* `/tmp/crate-build-riscv64-oa_sof97/src/alloca-0.4.0`

### Source file examples

* `/tmp/crate-build-riscv64-oa_sof97/src/alloca-0.4.0/alloca.c`

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/alloca-035daa7e144f7c43/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -mcmodel=medany -misa-spec=2.2 -march=rv64imafdc -gdwarf-4 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
