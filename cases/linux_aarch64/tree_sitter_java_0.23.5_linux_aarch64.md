# `tree-sitter-java` `0.23.5`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 813428

Build-script executable: `/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082`

Working directory: `/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/libtree-sitter-java.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5`

### Source directories

* `/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5/src`

### Source file examples

* `/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5/src/parser.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o -c src/parser.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -std=c11 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
