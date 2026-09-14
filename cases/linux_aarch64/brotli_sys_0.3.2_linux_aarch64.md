# `brotli-sys` `0.3.2`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 463431

Build-script executable: `/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f`

Working directory: `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2`

Full linker command: retained in the raw case.

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
