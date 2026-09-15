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

### Build-script executable native dependencies

#### Linker process 1938821

Build-script executable: `/work/target/debug/build/brotli-sys-c2e9e7289102ba5e/build_script_build-c2e9e7289102ba5e`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /work/target/debug/build/brotli-sys-54a7dfacae66a30e/out/e198953d800c79d4-dictionary.o -c brotli/common/dictionary.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I brotli/include -imultiarch x86_64-linux-gnu brotli/common/dictionary.c -quiet -dumpdir /work/target/debug/build/brotli-sys-54a7dfacae66a30e/out/ -dumpbase e198953d800c79d4-dictionary.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /work/target/debug/build/brotli-sys-54a7dfacae66a30e/out/76d4580618152496-bit_reader.o -c brotli/dec/bit_reader.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I brotli/include -imultiarch x86_64-linux-gnu brotli/dec/bit_reader.c -quiet -dumpdir /work/target/debug/build/brotli-sys-54a7dfacae66a30e/out/ -dumpbase 76d4580618152496-bit_reader.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /work/target/debug/build/brotli-sys-54a7dfacae66a30e/out/76d4580618152496-decode.o -c brotli/dec/decode.c
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -w -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
