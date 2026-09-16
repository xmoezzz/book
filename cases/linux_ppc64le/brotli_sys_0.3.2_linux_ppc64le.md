# `brotli-sys` `0.3.2`

Platform: Linux ppc64le

## Build-level coding evidence

### Source acquisition

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

```text
git submodule update --init
```

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

```text
/usr/bin/git submodule update --init
```

## `/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

### Source directories

* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/common`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc`

### Source file examples

* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/common/dictionary.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/bit_reader.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/decode.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/huffman.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/state.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o -c brotli/common/dictionary.c
```

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o -c brotli/dec/bit_reader.c
```

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o -c brotli/dec/decode.c
```

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o -c brotli/dec/huffman.c
```

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o -c brotli/dec/state.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -w -ffunction-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
