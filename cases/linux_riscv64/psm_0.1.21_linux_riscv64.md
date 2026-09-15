# `psm` `0.1.21`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 201533

Build-script executable: `/target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077`

Working directory: `/tmp/crate-build-riscv64-hq9ekr_c/src/psm-0.1.21`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/libpsm_s.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-hq9ekr_c/src/psm-0.1.21`

### Source directories

* `/tmp/crate-build-riscv64-hq9ekr_c/src/psm-0.1.21/src/arch`

### Source file examples

* `/tmp/crate-build-riscv64-hq9ekr_c/src/psm-0.1.21/src/arch/riscv64.s`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-hq9ekr_c/src/psm-0.1.21`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -mcmodel=medany -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_riscv64 -DCFG_TARGET_ENV_gnu -o /target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/src/arch/riscv64.o -c src/arch/riscv64.s ...
```

### Compilation

```text
cc1 -E -lang-asm -quiet -imultilib . -imultiarch riscv64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_riscv64 -D CFG_TARGET_ENV_gnu <source> -march=rv64gc -mabi=lp64d -mcmodel=medany -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
