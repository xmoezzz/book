# `tree-sitter-typescript` `0.23.2`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-typescript-8783607cd3571661/out/libtree-sitter-typescript.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-7x_m5_j1/src/tree-sitter-typescript-0.23.2`

### Source directories

* `/tmp/crate-build-aarch64-7x_m5_j1/src/tree-sitter-typescript-0.23.2/./tsx/src`
* `/tmp/crate-build-aarch64-7x_m5_j1/src/tree-sitter-typescript-0.23.2/./typescript/src`

### Source file examples

* `/tmp/crate-build-aarch64-7x_m5_j1/src/tree-sitter-typescript-0.23.2/./tsx/src/parser.c`
* `/tmp/crate-build-aarch64-7x_m5_j1/src/tree-sitter-typescript-0.23.2/./tsx/src/scanner.c`
* `/tmp/crate-build-aarch64-7x_m5_j1/src/tree-sitter-typescript-0.23.2/./typescript/src/parser.c`
* `/tmp/crate-build-aarch64-7x_m5_j1/src/tree-sitter-typescript-0.23.2/./typescript/src/scanner.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-7x_m5_j1/src/tree-sitter-typescript-0.23.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I ./typescript/src -Wall -Wextra -std=c11 -Wno-unused-parameter -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-typescript-8783607cd3571661/out/a423c62b91dd93af-parser.o -c ./typescript/src/parser.c
```

Working directory: `/tmp/crate-build-aarch64-7x_m5_j1/src/tree-sitter-typescript-0.23.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I ./typescript/src -Wall -Wextra -std=c11 -Wno-unused-parameter -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-typescript-8783607cd3571661/out/a423c62b91dd93af-scanner.o -c ./typescript/src/scanner.c
```

Working directory: `/tmp/crate-build-aarch64-7x_m5_j1/src/tree-sitter-typescript-0.23.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I ./typescript/src -Wall -Wextra -std=c11 -Wno-unused-parameter -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-typescript-8783607cd3571661/out/22f91614c58a9bd2-parser.o -c ./tsx/src/parser.c
```

Working directory: `/tmp/crate-build-aarch64-7x_m5_j1/src/tree-sitter-typescript-0.23.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I ./typescript/src -Wall -Wextra -std=c11 -Wno-unused-parameter -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-typescript-8783607cd3571661/out/22f91614c58a9bd2-scanner.o -c ./tsx/src/scanner.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-parameter ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
