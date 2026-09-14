# `tree-sitter-c` `0.23.4`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1030580

Build-script executable: `/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc`

Working directory: `/tmp/crate-build-ppc64le-zteeg1xf/src/tree-sitter-c-0.23.4`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/libtree-sitter-c.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-zteeg1xf/src/tree-sitter-c-0.23.4`

### Source directories

* `/tmp/crate-build-ppc64le-zteeg1xf/src/tree-sitter-c-0.23.4/src`

### Source file examples

* `/tmp/crate-build-ppc64le-zteeg1xf/src/tree-sitter-c-0.23.4/src/parser.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-zteeg1xf/src/tree-sitter-c-0.23.4`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/ea708c7824d36062-parser.o -c src/parser.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
