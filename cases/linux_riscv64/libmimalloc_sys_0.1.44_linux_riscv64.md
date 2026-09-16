# `libmimalloc-sys` `0.1.44`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/libmimalloc-sys-689d8d8161cb8e80/out/libmimalloc.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-bwzy2jxq/src/libmimalloc-sys-0.1.44`

### Source directories

* `/tmp/crate-build-riscv64-bwzy2jxq/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src`

### Source file examples

* `/tmp/crate-build-riscv64-bwzy2jxq/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src/static.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D MI_DEBUG=0 <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/libmimalloc-sys-689d8d8161cb8e80/out/ -dumpbase <source> -dumpbase-ext .c ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
