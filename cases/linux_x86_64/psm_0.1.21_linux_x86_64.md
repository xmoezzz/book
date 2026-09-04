# `psm` `0.1.21`

Platform: Linux x86_64

## `/work/target/debug/build/psm-0f015c94365d0864/out/libpsm_s.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src/arch`

### Source file examples

* `/work/src/arch/x86_64.s`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_x86_64 -DCFG_TARGET_ENV_gnu -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
