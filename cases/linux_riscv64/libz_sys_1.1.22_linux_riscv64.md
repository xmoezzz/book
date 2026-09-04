# `libz-sys` `1.1.22`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-0abeca708df47ab6/out/lib/libz.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-3p817b79/src/libz-sys-1.1.22`

### Source directories

* `/tmp/crate-build-riscv64-3p817b79/src/libz-sys-1.1.22/src/zlib`

### Source file examples

* `/tmp/crate-build-riscv64-3p817b79/src/libz-sys-1.1.22/src/zlib/adler32.c`
* `/tmp/crate-build-riscv64-3p817b79/src/libz-sys-1.1.22/src/zlib/compress.c`
* `/tmp/crate-build-riscv64-3p817b79/src/libz-sys-1.1.22/src/zlib/crc32.c`
* `/tmp/crate-build-riscv64-3p817b79/src/libz-sys-1.1.22/src/zlib/deflate.c`
* `/tmp/crate-build-riscv64-3p817b79/src/libz-sys-1.1.22/src/zlib/gzclose.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D STDC -D _LARGEFILE64_SOURCE -D _POSIX_SOURCE <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-0abeca708df47ab6/out/lib/ -dumpbase <source> ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
