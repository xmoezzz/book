# `minicov` `0.3.7`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 1958247

Build-script executable: `/work/target/debug/build/minicov-2650417fc3710a41/build_script_build-2650417fc3710a41`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/minicov-f7a5535faf81c83e/out/libllvm_profiler_runtime.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/c`

### Source file examples

* `/work/c/InstrProfiling.c`
* `/work/c/InstrProfilingBuffer.c`
* `/work/c/InstrProfilingInternal.c`
* `/work/c/InstrProfilingMerge.c`
* `/work/c/InstrProfilingPlatformLinux.c`

### Compilation

```text
clang -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 --target=x86_64-unknown-linux-gnu -Wall -Wextra -nostdlibinc -fno-stack-protector -fno-profile-instr-generate -fno-coverage-mapping -DCOMPILER_RT_HAS_ATOMICS=1 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
