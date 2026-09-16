# `wasmtime-runtime` `8.0.1`

Platform: Linux x86_64

## `/work/target/debug/build/wasmtime-runtime-bf2fe768efeaa438/out/libwasmtime-helpers.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/helpers.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_x86_64 -o /work/target/debug/build/wasmtime-runtime-bf2fe768efeaa438/out/ea708c7824d36062-helpers.o -c src/helpers.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_x86_64 src/helpers.c -quiet -dumpdir /work/target/debug/build/wasmtime-runtime-bf2fe768efeaa438/out/ -dumpbase ea708c7824d36062-helpers.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_x86_64 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
