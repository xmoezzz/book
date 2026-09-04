# `bzip2-sys` `0.1.11+1.0.8`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/bzip2-sys-6637d23fd95410b5/out/lib/libbz2.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8`

### Source directories

* `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8`

### Source file examples

* `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/blocksort.c`
* `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/bzlib.c`
* `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/compress.c`
* `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/crctable.c`
* `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/decompress.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D _FILE_OFFSET_BITS=64 -D BZ_NO_STDIO <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/bzip2-sys-6637d23fd95410b5/out/lib/ -dumpbase <source> -dumpbase-ext .c ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
