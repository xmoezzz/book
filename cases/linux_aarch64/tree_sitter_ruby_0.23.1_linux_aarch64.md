# `tree-sitter-ruby` `0.23.1`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-ruby-de7076b607be3a88/out/libtree-sitter-ruby.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-vu8x9337/src/tree-sitter-ruby-0.23.1`

### Source directories

* `/tmp/crate-build-aarch64-vu8x9337/src/tree-sitter-ruby-0.23.1/src`

### Source file examples

* `/tmp/crate-build-aarch64-vu8x9337/src/tree-sitter-ruby-0.23.1/src/parser.c`
* `/tmp/crate-build-aarch64-vu8x9337/src/tree-sitter-ruby-0.23.1/src/scanner.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-vu8x9337/src/tree-sitter-ruby-0.23.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-ruby-de7076b607be3a88/out/ea708c7824d36062-parser.o -c src/parser.c
```

Working directory: `/tmp/crate-build-aarch64-vu8x9337/src/tree-sitter-ruby-0.23.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-ruby-de7076b607be3a88/out/ea708c7824d36062-scanner.o -c src/scanner.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-value ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
