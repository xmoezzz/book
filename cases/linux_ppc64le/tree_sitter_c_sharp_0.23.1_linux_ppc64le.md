# `tree-sitter-c-sharp` `0.23.1`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-fc0e9c4da73c90da/out/libtree-sitter-c-sharp.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-8vp4mis_/src/tree-sitter-c-sharp-0.23.1`

### Source directories

* `/tmp/crate-build-ppc64le-8vp4mis_/src/tree-sitter-c-sharp-0.23.1/src`

### Source file examples

* `/tmp/crate-build-ppc64le-8vp4mis_/src/tree-sitter-c-sharp-0.23.1/src/parser.c`
* `/tmp/crate-build-ppc64le-8vp4mis_/src/tree-sitter-c-sharp-0.23.1/src/scanner.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-8vp4mis_/src/tree-sitter-c-sharp-0.23.1`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-fc0e9c4da73c90da/out/ea708c7824d36062-parser.o -c src/parser.c
```

Working directory: `/tmp/crate-build-ppc64le-8vp4mis_/src/tree-sitter-c-sharp-0.23.1`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-fc0e9c4da73c90da/out/ea708c7824d36062-scanner.o -c src/scanner.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
