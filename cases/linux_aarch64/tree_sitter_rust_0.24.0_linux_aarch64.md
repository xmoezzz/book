# `tree-sitter-rust` `0.24.0`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-rust-972680a6ff9e58a0/out/libtree-sitter-rust.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-33mk18n9/src/tree-sitter-rust-0.24.0`

### Source directories

* `/tmp/crate-build-aarch64-33mk18n9/src/tree-sitter-rust-0.24.0/src`

### Source file examples

* `/tmp/crate-build-aarch64-33mk18n9/src/tree-sitter-rust-0.24.0/src/parser.c`
* `/tmp/crate-build-aarch64-33mk18n9/src/tree-sitter-rust-0.24.0/src/scanner.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-33mk18n9/src/tree-sitter-rust-0.24.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-rust-972680a6ff9e58a0/out/ea708c7824d36062-parser.o -c src/parser.c
```

Working directory: `/tmp/crate-build-aarch64-33mk18n9/src/tree-sitter-rust-0.24.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-rust-972680a6ff9e58a0/out/ea708c7824d36062-scanner.o -c src/scanner.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -std=c11 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
