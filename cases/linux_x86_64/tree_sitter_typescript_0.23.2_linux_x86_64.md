# `tree-sitter-typescript` `0.23.2`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 2046825

Build-script executable: `/work/target/debug/build/tree-sitter-typescript-39c2c413195ebe6b/build_script_build-39c2c413195ebe6b`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/tree-sitter-typescript-81eb30820e635f54/out/libtree-sitter-typescript.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/./tsx/src`
* `/work/./typescript/src`

### Source file examples

* `/work/./tsx/src/parser.c`
* `/work/./tsx/src/scanner.c`
* `/work/./typescript/src/parser.c`
* `/work/./typescript/src/scanner.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I ./typescript/src -Wall -Wextra -o /work/target/debug/build/tree-sitter-typescript-81eb30820e635f54/out/a423c62b91dd93af-parser.o -c ./typescript/src/parser.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I ./typescript/src -imultiarch x86_64-linux-gnu ./typescript/src/parser.c -quiet -dumpdir /work/target/debug/build/tree-sitter-typescript-81eb30820e635f54/out/ -dumpbase a423c62b91dd93af-parser.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I ./typescript/src -Wall -Wextra -o /work/target/debug/build/tree-sitter-typescript-81eb30820e635f54/out/a423c62b91dd93af-scanner.o -c ./typescript/src/scanner.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I ./typescript/src -imultiarch x86_64-linux-gnu ./typescript/src/scanner.c -quiet -dumpdir /work/target/debug/build/tree-sitter-typescript-81eb30820e635f54/out/ -dumpbase a423c62b91dd93af-scanner.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I ./typescript/src -Wall -Wextra -o /work/target/debug/build/tree-sitter-typescript-81eb30820e635f54/out/22f91614c58a9bd2-parser.o -c ./tsx/src/parser.c
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
