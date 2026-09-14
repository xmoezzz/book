# `tree-sitter-python` `0.23.6`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 2099747

Build-script executable: `/work/target/debug/build/tree-sitter-python-3836ce6b0987be83/build_script_build-3836ce6b0987be83`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/tree-sitter-python-5f04eed42773a939/out/libtree-sitter-python.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/parser.c`
* `/work/src/scanner.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -o /work/target/debug/build/tree-sitter-python-5f04eed42773a939/out/ea708c7824d36062-parser.o -c src/parser.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I src -imultiarch x86_64-linux-gnu src/parser.c -quiet -dumpdir /work/target/debug/build/tree-sitter-python-5f04eed42773a939/out/ -dumpbase ea708c7824d36062-parser.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I src -imultiarch x86_64-linux-gnu src/scanner.c -quiet -dumpdir /work/target/debug/build/tree-sitter-python-5f04eed42773a939/out/ -dumpbase ea708c7824d36062-scanner.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -o /work/target/debug/build/tree-sitter-python-5f04eed42773a939/out/ea708c7824d36062-scanner.o -c src/scanner.c
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I <include directory> -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
