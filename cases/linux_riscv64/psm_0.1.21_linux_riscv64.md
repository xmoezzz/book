# `psm` `0.1.21`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/libpsm_s.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-hq9ekr_c/src/psm-0.1.21`

### Source directories

* `/tmp/crate-build-riscv64-hq9ekr_c/src/psm-0.1.21/src/arch`

### Source file examples

* `/tmp/crate-build-riscv64-hq9ekr_c/src/psm-0.1.21/src/arch/riscv64.s`

### Compilation

```text
cc1 -E -lang-asm -quiet -imultilib . -imultiarch riscv64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_riscv64 -D CFG_TARGET_ENV_gnu <source> -march=rv64gc -mabi=lp64d -mcmodel=medany -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
