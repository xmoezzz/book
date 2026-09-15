# `bzip2-sys` `0.1.11+1.0.8`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 80739

Build-script executable: `/target/debug/build/bzip2-sys-785406d8a50bc4a0/build_script_build-785406d8a50bc4a0`

Working directory: `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/aarch64-unknown-linux-gnu/debug/build/bzip2-sys-33c03a045fd6497b/out/lib/libbz2.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8`

### Source directories

* `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8`

### Source file examples

* `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/blocksort.c`
* `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/bzlib.c`
* `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/compress.c`
* `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/crctable.c`
* `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/decompress.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/aarch64-unknown-linux-gnu/debug/build/bzip2-sys-33c03a045fd6497b/out/lib/a9dc8ba631b1466a-blocksort.o -c bzip2-1.0.8/blocksort.c
```

Working directory: `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/aarch64-unknown-linux-gnu/debug/build/bzip2-sys-33c03a045fd6497b/out/lib/a9dc8ba631b1466a-huffman.o -c bzip2-1.0.8/huffman.c
```

Working directory: `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I bzip2-1.0.8 -imultiarch aarch64-linux-gnu -D _FILE_OFFSET_BITS=64 -D BZ_NO_STDIO bzip2-1.0.8/crctable.c -quiet -dumpbase crctable.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/bzip2-sys-33c03a045fd6497b/out/lib/a9dc8ba631b1466a-crctable.o -g -gdwarf-4 ...
```

Working directory: `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/aarch64-unknown-linux-gnu/debug/build/bzip2-sys-33c03a045fd6497b/out/lib/a9dc8ba631b1466a-randtable.o -c bzip2-1.0.8/randtable.c
```

Working directory: `/tmp/crate-build-aarch64-xnm4tyeh/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/aarch64-unknown-linux-gnu/debug/build/bzip2-sys-33c03a045fd6497b/out/lib/a9dc8ba631b1466a-compress.o -c bzip2-1.0.8/compress.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu -D _FILE_OFFSET_BITS=64 -D BZ_NO_STDIO <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I <include directory> -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
