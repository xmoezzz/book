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

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
