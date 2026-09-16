# `bzip2-sys` `0.1.11+1.0.8`

Platform: Linux x86_64

## `/work/target/debug/build/bzip2-sys-4639fd76dec3968e/out/lib/libbz2.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/bzip2-1.0.8`

### Source file examples

* `/work/bzip2-1.0.8/blocksort.c`
* `/work/bzip2-1.0.8/bzlib.c`
* `/work/bzip2-1.0.8/compress.c`
* `/work/bzip2-1.0.8/crctable.c`
* `/work/bzip2-1.0.8/decompress.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /work/target/debug/build/bzip2-sys-4639fd76dec3968e/out/lib/a9dc8ba631b1466a-blocksort.o -c bzip2-1.0.8/blocksort.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I bzip2-1.0.8 -imultiarch x86_64-linux-gnu -D _FILE_OFFSET_BITS=64 -D BZ_NO_STDIO bzip2-1.0.8/blocksort.c -quiet -dumpdir /work/target/debug/build/bzip2-sys-4639fd76dec3968e/out/lib/ -dumpbase a9dc8ba631b1466a-blocksort.c -dumpbase-ext .c -m64 -mtune=generic ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /work/target/debug/build/bzip2-sys-4639fd76dec3968e/out/lib/a9dc8ba631b1466a-huffman.o -c bzip2-1.0.8/huffman.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I bzip2-1.0.8 -imultiarch x86_64-linux-gnu -D _FILE_OFFSET_BITS=64 -D BZ_NO_STDIO bzip2-1.0.8/huffman.c -quiet -dumpdir /work/target/debug/build/bzip2-sys-4639fd76dec3968e/out/lib/ -dumpbase a9dc8ba631b1466a-huffman.c -dumpbase-ext .c -m64 -mtune=generic ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /work/target/debug/build/bzip2-sys-4639fd76dec3968e/out/lib/a9dc8ba631b1466a-crctable.o -c bzip2-1.0.8/crctable.c
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
