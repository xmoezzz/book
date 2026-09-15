# `psm` `0.1.21`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 202302

Build-script executable: `/target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077`

Working directory: `/tmp/crate-build-ppc64le-bgdfexpp/src/psm-0.1.21`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/libpsm_s.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-bgdfexpp/src/psm-0.1.21`

### Source directories

* `/tmp/crate-build-ppc64le-bgdfexpp/src/psm-0.1.21/src/arch`

### Source file examples

* `/tmp/crate-build-ppc64le-bgdfexpp/src/psm-0.1.21/src/arch/powerpc64_openpower.s`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-bgdfexpp/src/psm-0.1.21`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_powerpc64 -DCFG_TARGET_ENV_gnu -o /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o -c src/arch/powerpc64_openpower.s
```

### Compilation

```text
cc1 -E -lang-asm -quiet -imultiarch powerpc64le-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_powerpc64 -D CFG_TARGET_ENV_gnu <source> -msecure-plt -m64 -mcpu=power8 -Wall -Wextra -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
