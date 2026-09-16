# `psm` `0.1.21`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/psm-b0eef911462470fc/out/libpsm_s.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-l9o3u8nr/src/psm-0.1.21`

### Source directories

* `/tmp/crate-build-aarch64-l9o3u8nr/src/psm-0.1.21/src/arch`

### Source file examples

* `/tmp/crate-build-aarch64-l9o3u8nr/src/psm-0.1.21/src/arch/aarch_aapcs64.s`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-l9o3u8nr/src/psm-0.1.21`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_aarch64 -DCFG_TARGET_ENV_gnu -o /target/aarch64-unknown-linux-gnu/debug/build/psm-b0eef911462470fc/out/src/arch/aarch_aapcs64.o -c src/arch/aarch_aapcs64.s
```

### Compilation

```text
cc1 -E -lang-asm -quiet -imultiarch aarch64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_aarch64 -D CFG_TARGET_ENV_gnu <source> -mlittle-endian -mabi=lp64 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
