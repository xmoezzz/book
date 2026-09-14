# `tree-sitter-c-sharp` `0.23.1`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1063159

Build-script executable: `/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201`

Working directory: `/tmp/crate-build-aarch64-xuhkm4x_/src/tree-sitter-c-sharp-0.23.1`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/libtree-sitter-c-sharp.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-xuhkm4x_/src/tree-sitter-c-sharp-0.23.1`

### Source directories

* `/tmp/crate-build-aarch64-xuhkm4x_/src/tree-sitter-c-sharp-0.23.1/src`

### Source file examples

* `/tmp/crate-build-aarch64-xuhkm4x_/src/tree-sitter-c-sharp-0.23.1/src/parser.c`
* `/tmp/crate-build-aarch64-xuhkm4x_/src/tree-sitter-c-sharp-0.23.1/src/scanner.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-xuhkm4x_/src/tree-sitter-c-sharp-0.23.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o -c src/parser.c
```

Working directory: `/tmp/crate-build-aarch64-xuhkm4x_/src/tree-sitter-c-sharp-0.23.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-scanner.o -c src/scanner.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-value ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
