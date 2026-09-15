# `bzip2-sys` `0.1.11+1.0.8`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 80818

Build-script executable: `/target/debug/build/bzip2-sys-785406d8a50bc4a0/build_script_build-785406d8a50bc4a0`

Working directory: `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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

### Source preparation

Working directory: `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/riscv64gc-unknown-linux-gnu/debug/build/bzip2-sys-6637d23fd95410b5/out/lib/a9dc8ba631b1466a-blocksort.o -c bzip2-1.0.8/blocksort.c
```

Working directory: `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/riscv64gc-unknown-linux-gnu/debug/build/bzip2-sys-6637d23fd95410b5/out/lib/a9dc8ba631b1466a-huffman.o -c bzip2-1.0.8/huffman.c
```

Working directory: `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/riscv64gc-unknown-linux-gnu/debug/build/bzip2-sys-6637d23fd95410b5/out/lib/a9dc8ba631b1466a-crctable.o -c bzip2-1.0.8/crctable.c
```

Working directory: `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/riscv64gc-unknown-linux-gnu/debug/build/bzip2-sys-6637d23fd95410b5/out/lib/a9dc8ba631b1466a-randtable.o -c bzip2-1.0.8/randtable.c
```

Working directory: `/tmp/crate-build-riscv64-f8p9lsan/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/riscv64gc-unknown-linux-gnu/debug/build/bzip2-sys-6637d23fd95410b5/out/lib/a9dc8ba631b1466a-compress.o -c bzip2-1.0.8/compress.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D _FILE_OFFSET_BITS=64 -D BZ_NO_STDIO <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/bzip2-sys-6637d23fd95410b5/out/lib/ -dumpbase <source> -dumpbase-ext .c ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
