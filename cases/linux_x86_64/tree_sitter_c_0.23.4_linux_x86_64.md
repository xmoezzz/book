# `tree-sitter-c` `0.23.4`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 2144030

Build-script executable: `/work/target/debug/build/tree-sitter-c-78f9e2739dae3246/build_script_build-78f9e2739dae3246`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/tree-sitter-c-c5c0f05a3687ceb1/out/libtree-sitter-c.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/parser.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -o /work/target/debug/build/tree-sitter-c-c5c0f05a3687ceb1/out/ea708c7824d36062-parser.o -c src/parser.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I src -imultiarch x86_64-linux-gnu src/parser.c -quiet -dumpdir /work/target/debug/build/tree-sitter-c-c5c0f05a3687ceb1/out/ -dumpbase ea708c7824d36062-parser.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I <include directory> -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
