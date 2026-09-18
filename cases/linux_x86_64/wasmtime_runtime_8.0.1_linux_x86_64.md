# `wasmtime-runtime` `8.0.1`

Platform: Linux x86_64

## `/work/target/debug/build/wasmtime-runtime-bf2fe768efeaa438/out/libwasmtime-helpers.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/helpers.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_x86_64 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
