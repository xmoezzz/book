# `minicov` `0.3.7`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 513950

Build-script executable: `/target/debug/build/minicov-cf5e8875ec696c31/build_script_build-cf5e8875ec696c31`

Working directory: `/tmp/crate-build-riscv64-fiqdyj1a/src/minicov-0.3.7`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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
