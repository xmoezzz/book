# `minicov` `0.3.7`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/minicov-7310a24a5ad18f32/out/libllvm_profiler_runtime.a`

### Source origin

* matches Linux x86_64 source path `/work/c/InstrProfiling.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingBuffer.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingInternal.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingMerge.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingPlatformLinux.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingPlatformOther.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingPlatformWindows.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingValue.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingVersionVar.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingWriter.c`, under crate source directory `/work`

### Source directories

* `c`

### Source file examples

* `c/InstrProfiling.c`
* `c/InstrProfilingBuffer.c`
* `c/InstrProfilingInternal.c`
* `c/InstrProfilingMerge.c`
* `c/InstrProfilingPlatformLinux.c`

### Compilation

```text
clang -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer --target=riscv64-unknown-linux-gnu -Wall -Wextra -nostdlibinc -fno-stack-protector -fno-profile-instr-generate -fno-coverage-mapping -DCOMPILER_RT_HAS_ATOMICS=1 -o <object> -c <source> ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
