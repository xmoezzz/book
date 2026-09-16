# `wasmtime-runtime` `8.0.1`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/wasmtime-runtime-bf12678ed4790af9/out/libwasmtime-helpers.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-a7fz7ila/src/wasmtime-runtime-8.0.1`

### Source directories

* `/tmp/crate-build-riscv64-a7fz7ila/src/wasmtime-runtime-8.0.1/src`

### Source file examples

* `/tmp/crate-build-riscv64-a7fz7ila/src/wasmtime-runtime-8.0.1/src/helpers.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-a7fz7ila/src/wasmtime-runtime-8.0.1`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_riscv64 -o /target/riscv64gc-unknown-linux-gnu/debug/build/wasmtime-runtime-bf12678ed4790af9/out/ea708c7824d36062-helpers.o -c src/helpers.c
```

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_riscv64 <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/wasmtime-runtime-bf12678ed4790af9/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
