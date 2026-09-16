# `brotli-sys` `0.3.2`

Platform: Linux aarch64

## Build-level coding evidence

### Source acquisition

Working directory: `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2`

```text
git submodule update --init
```

Working directory: `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2`

```text
/usr/bin/git submodule update --init
```

## `/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/libbrotli.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2`

### Source directories

* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/common`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/dec`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc`

### Source file examples

* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/common/dictionary.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/dec/bit_reader.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/dec/decode.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/dec/huffman.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/dec/state.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I brotli/include -w -o /target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o -c brotli/dec/bit_reader.c
```

Working directory: `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I brotli/include -w -o /target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o -c brotli/dec/decode.c
```

Working directory: `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I brotli/include -w -o /target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o -c brotli/dec/state.c
```

Working directory: `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I brotli/include -w -o /target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o -c brotli/enc/backward_references.c
```

Working directory: `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I brotli/include -w -o /target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o -c brotli/enc/bit_cost.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -w -ffunction-sections -fdata-sections ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I <include directory> -w -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
