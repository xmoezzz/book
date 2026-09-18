# `blst` `0.3.16`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/blst-3351224bbbe670bb/out/libblst.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-84usivvg/src/blst-0.3.16`

### Source directories

* `/tmp/crate-build-riscv64-84usivvg/src/blst-0.3.16/blst/src`

### Source file examples

* `/tmp/crate-build-riscv64-84usivvg/src/blst-0.3.16/blst/src/server.c`

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -D __BLST_NO_ASM__ <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/blst-3351224bbbe670bb/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
