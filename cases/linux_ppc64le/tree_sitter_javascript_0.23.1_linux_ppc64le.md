# `tree-sitter-javascript` `0.23.1`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-javascript-895296eac68be886/out/libtree-sitter-javascript.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-p0208nuq/src/tree-sitter-javascript-0.23.1`

### Source directories

* `/tmp/crate-build-ppc64le-p0208nuq/src/tree-sitter-javascript-0.23.1/src`

### Source file examples

* `/tmp/crate-build-ppc64le-p0208nuq/src/tree-sitter-javascript-0.23.1/src/parser.c`
* `/tmp/crate-build-ppc64le-p0208nuq/src/tree-sitter-javascript-0.23.1/src/scanner.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-p0208nuq/src/tree-sitter-javascript-0.23.1`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -Wno-unused-parameter -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-javascript-895296eac68be886/out/ea708c7824d36062-parser.o -c src/parser.c
```

Working directory: `/tmp/crate-build-ppc64le-p0208nuq/src/tree-sitter-javascript-0.23.1`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -Wno-unused-parameter -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-javascript-895296eac68be886/out/ea708c7824d36062-scanner.o -c src/scanner.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
