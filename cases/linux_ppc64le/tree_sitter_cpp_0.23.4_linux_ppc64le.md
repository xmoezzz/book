# `tree-sitter-cpp` `0.23.4`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 811216

Build-script executable: `/target/debug/build/tree-sitter-cpp-73fc54233518dbc6/build_script_build-73fc54233518dbc6`

Working directory: `/tmp/crate-build-ppc64le-_6ctj1sy/src/tree-sitter-cpp-0.23.4`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-cpp-27e536107a6ea40c/out/libtree-sitter-cpp.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-_6ctj1sy/src/tree-sitter-cpp-0.23.4`

### Source directories

* `/tmp/crate-build-ppc64le-_6ctj1sy/src/tree-sitter-cpp-0.23.4/src`

### Source file examples

* `/tmp/crate-build-ppc64le-_6ctj1sy/src/tree-sitter-cpp-0.23.4/src/parser.c`
* `/tmp/crate-build-ppc64le-_6ctj1sy/src/tree-sitter-cpp-0.23.4/src/scanner.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-_6ctj1sy/src/tree-sitter-cpp-0.23.4`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-cpp-27e536107a6ea40c/out/ea708c7824d36062-parser.o -c src/parser.c
```

Working directory: `/tmp/crate-build-ppc64le-_6ctj1sy/src/tree-sitter-cpp-0.23.4`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-cpp-27e536107a6ea40c/out/ea708c7824d36062-scanner.o -c src/scanner.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
