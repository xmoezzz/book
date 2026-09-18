# `brotli-sys` `0.3.2`

Platform: Linux x86_64

## Build-level coding evidence

### Source acquisition

Working directory: `/work`

```text
git submodule update --init
```

Working directory: `/work`

```text
/usr/bin/git submodule update --init
```

## `/work/target/debug/build/brotli-sys-54a7dfacae66a30e/out/libbrotli.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/brotli/common`
* `/work/brotli/dec`
* `/work/brotli/enc`

### Source file examples

* `/work/brotli/common/dictionary.c`
* `/work/brotli/dec/bit_reader.c`
* `/work/brotli/dec/decode.c`
* `/work/brotli/dec/huffman.c`
* `/work/brotli/dec/state.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -w -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
