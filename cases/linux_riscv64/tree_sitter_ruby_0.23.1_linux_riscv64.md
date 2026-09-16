# `tree-sitter-ruby` `0.23.1`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-ruby-a9670fc148d37df1/out/libtree-sitter-ruby.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-mh6enxfk/src/tree-sitter-ruby-0.23.1`

### Source directories

* `/tmp/crate-build-riscv64-mh6enxfk/src/tree-sitter-ruby-0.23.1/src`

### Source file examples

* `/tmp/crate-build-riscv64-mh6enxfk/src/tree-sitter-ruby-0.23.1/src/parser.c`
* `/tmp/crate-build-riscv64-mh6enxfk/src/tree-sitter-ruby-0.23.1/src/scanner.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-mh6enxfk/src/tree-sitter-ruby-0.23.1`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-ruby-a9670fc148d37df1/out/ea708c7824d36062-parser.o -c src/parser.c ...
```

Working directory: `/tmp/crate-build-riscv64-mh6enxfk/src/tree-sitter-ruby-0.23.1`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-ruby-a9670fc148d37df1/out/ea708c7824d36062-scanner.o -c src/scanner.c ...
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-ruby-a9670fc148d37df1/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
