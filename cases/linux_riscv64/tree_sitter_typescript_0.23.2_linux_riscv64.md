# `tree-sitter-typescript` `0.23.2`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-typescript-37f686424ce8c7f1/out/libtree-sitter-typescript.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-w32o3jui/src/tree-sitter-typescript-0.23.2`

### Source directories

* `/tmp/crate-build-riscv64-w32o3jui/src/tree-sitter-typescript-0.23.2/./tsx/src`
* `/tmp/crate-build-riscv64-w32o3jui/src/tree-sitter-typescript-0.23.2/./typescript/src`

### Source file examples

* `/tmp/crate-build-riscv64-w32o3jui/src/tree-sitter-typescript-0.23.2/./tsx/src/parser.c`
* `/tmp/crate-build-riscv64-w32o3jui/src/tree-sitter-typescript-0.23.2/./tsx/src/scanner.c`
* `/tmp/crate-build-riscv64-w32o3jui/src/tree-sitter-typescript-0.23.2/./typescript/src/parser.c`
* `/tmp/crate-build-riscv64-w32o3jui/src/tree-sitter-typescript-0.23.2/./typescript/src/scanner.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-w32o3jui/src/tree-sitter-typescript-0.23.2`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I ./typescript/src -Wall -Wextra -std=c11 -Wno-unused-parameter -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-typescript-37f686424ce8c7f1/out/a423c62b91dd93af-parser.o -c ./typescript/src/parser.c ...
```

Working directory: `/tmp/crate-build-riscv64-w32o3jui/src/tree-sitter-typescript-0.23.2`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I ./typescript/src -Wall -Wextra -std=c11 -Wno-unused-parameter -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-typescript-37f686424ce8c7f1/out/a423c62b91dd93af-scanner.o -c ./typescript/src/scanner.c ...
```

Working directory: `/tmp/crate-build-riscv64-w32o3jui/src/tree-sitter-typescript-0.23.2`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I ./typescript/src -Wall -Wextra -std=c11 -Wno-unused-parameter -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-typescript-37f686424ce8c7f1/out/22f91614c58a9bd2-parser.o -c ./tsx/src/parser.c ...
```

Working directory: `/tmp/crate-build-riscv64-w32o3jui/src/tree-sitter-typescript-0.23.2`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I ./typescript/src -Wall -Wextra -std=c11 -Wno-unused-parameter -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-typescript-37f686424ce8c7f1/out/22f91614c58a9bd2-scanner.o -c ./tsx/src/scanner.c ...
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-typescript-37f686424ce8c7f1/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
