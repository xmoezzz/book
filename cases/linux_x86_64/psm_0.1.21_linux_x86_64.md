# `psm` `0.1.21`

Platform: Linux x86_64

## `/work/target/debug/build/psm-0f015c94365d0864/out/libpsm_s.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src/arch`

### Source file examples

* `/work/src/arch/x86_64.s`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_x86_64 -DCFG_TARGET_ENV_gnu -o /work/target/debug/build/psm-0f015c94365d0864/out/src/arch/x86_64.o -c src/arch/x86_64.s
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -E -lang-asm -quiet -imultiarch x86_64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_x86_64 -D CFG_TARGET_ENV_gnu src/arch/x86_64.s -m64 -mtune=generic -march=x86-64 -Wall -Wextra -ffunction-sections -fdata-sections ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_x86_64 -DCFG_TARGET_ENV_gnu -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
