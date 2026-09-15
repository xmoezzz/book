# `bzip2-sys` `0.1.11+1.0.8`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 80618

Build-script executable: `/target/debug/build/bzip2-sys-785406d8a50bc4a0/build_script_build-785406d8a50bc4a0`

Working directory: `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/bzip2-sys-cf8425bba4418423/out/lib/libbz2.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8`

### Source directories

* `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8`

### Source file examples

* `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/blocksort.c`
* `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/bzlib.c`
* `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/compress.c`
* `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/crctable.c`
* `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/decompress.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/powerpc64le-unknown-linux-gnu/debug/build/bzip2-sys-cf8425bba4418423/out/lib/a9dc8ba631b1466a-blocksort.o -c bzip2-1.0.8/blocksort.c
```

Working directory: `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/powerpc64le-unknown-linux-gnu/debug/build/bzip2-sys-cf8425bba4418423/out/lib/a9dc8ba631b1466a-huffman.o -c bzip2-1.0.8/huffman.c
```

Working directory: `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/powerpc64le-unknown-linux-gnu/debug/build/bzip2-sys-cf8425bba4418423/out/lib/a9dc8ba631b1466a-crctable.o -c bzip2-1.0.8/crctable.c
```

Working directory: `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/powerpc64le-unknown-linux-gnu/debug/build/bzip2-sys-cf8425bba4418423/out/lib/a9dc8ba631b1466a-randtable.o -c bzip2-1.0.8/randtable.c
```

Working directory: `/tmp/crate-build-ppc64le-pr_c1pm8/src/bzip2-sys-0.1.11+1.0.8`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I bzip2-1.0.8 -w -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO -o /target/powerpc64le-unknown-linux-gnu/debug/build/bzip2-sys-cf8425bba4418423/out/lib/a9dc8ba631b1466a-compress.o -c bzip2-1.0.8/compress.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu -D _FILE_OFFSET_BITS=64 -D BZ_NO_STDIO <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
