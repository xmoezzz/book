# `wasmtime-runtime` `8.0.1`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/wasmtime-runtime-54c203e6228eed37/out/libwasmtime-helpers.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-axwoxy51/src/wasmtime-runtime-8.0.1`

### Source directories

* `/tmp/crate-build-aarch64-axwoxy51/src/wasmtime-runtime-8.0.1/src`

### Source file examples

* `/tmp/crate-build-aarch64-axwoxy51/src/wasmtime-runtime-8.0.1/src/helpers.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-axwoxy51/src/wasmtime-runtime-8.0.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_aarch64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasmtime-runtime-54c203e6228eed37/out/ea708c7824d36062-helpers.o -c src/helpers.c
```

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_aarch64 <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
