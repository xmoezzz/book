# `psm` `0.1.21`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1847719

Build-script executable: `/work/target/debug/build/psm-26c8bd77d569aca4/build_script_build-26c8bd77d569aca4`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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
