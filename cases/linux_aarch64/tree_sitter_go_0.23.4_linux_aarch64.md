# `tree-sitter-go` `0.23.4`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-go-53209227a1720313/out/libtree-sitter-go.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-wdafjz9u/src/tree-sitter-go-0.23.4`

### Source directories

* `/tmp/crate-build-aarch64-wdafjz9u/src/tree-sitter-go-0.23.4/src`

### Source file examples

* `/tmp/crate-build-aarch64-wdafjz9u/src/tree-sitter-go-0.23.4/src/parser.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-wdafjz9u/src/tree-sitter-go-0.23.4`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-go-53209227a1720313/out/ea708c7824d36062-parser.o -c src/parser.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -std=c11 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
