# `brotli-sys` `0.3.2`

Platform: Linux ppc64le

## Build-level coding evidence

### Network / source acquisition activity

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

```text
git submodule update --init
```

Acquisition kind: `git_submodule`

Outcome: failed (exit code 128)

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

```text
/usr/bin/git submodule update --init
```

Outcome: outcome unavailable in trace

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 467240

Build-script executable: `/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f`

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

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
