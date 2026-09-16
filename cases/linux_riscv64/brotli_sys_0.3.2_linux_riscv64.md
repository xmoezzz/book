# `brotli-sys` `0.3.2`

Platform: Linux riscv64

## Build-level coding evidence

### Source acquisition

Working directory: `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2`

```text
git submodule update --init
```

Working directory: `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2`

```text
/usr/bin/git submodule update --init
```

## `/target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2`

### Source directories

* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/common`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/dec`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/enc`

### Source file examples

* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/common/dictionary.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/dec/bit_reader.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/dec/decode.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/dec/huffman.c`
* `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2/brotli/dec/state.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o -c brotli/common/dictionary.c
```

Working directory: `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o -c brotli/dec/bit_reader.c
```

Working directory: `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o -c brotli/dec/decode.c
```

Working directory: `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o -c brotli/dec/huffman.c
```

Working directory: `/tmp/crate-build-riscv64-zwf8l4r8/src/brotli-sys-0.3.2`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o -c brotli/dec/state.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
