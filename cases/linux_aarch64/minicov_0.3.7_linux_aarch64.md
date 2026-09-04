# `minicov` `0.3.7`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/minicov-a741e09b7757f515/out/libllvm_profiler_runtime.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-tr935jbb/src/minicov-0.3.7`
* matches Linux x86_64 source path `/work/c/InstrProfiling.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingBuffer.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingInternal.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingMerge.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingPlatformLinux.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingPlatformOther.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingValue.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingVersionVar.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/c/InstrProfilingWriter.c`, under crate source directory `/work`

### Source directories

* `/tmp/crate-build-aarch64-tr935jbb/src/minicov-0.3.7/c`
* `c`

### Source file examples

* `/tmp/crate-build-aarch64-tr935jbb/src/minicov-0.3.7/c/InstrProfilingPlatformWindows.c`
* `c/InstrProfiling.c`
* `c/InstrProfilingBuffer.c`
* `c/InstrProfilingInternal.c`
* `c/InstrProfilingMerge.c`

### Compilation

```text
clang -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer --target=aarch64-unknown-linux-gnu -Wall -Wextra -nostdlibinc -fno-stack-protector -fno-profile-instr-generate -fno-coverage-mapping -DCOMPILER_RT_HAS_ATOMICS=1 -o <object> -c <source>
```

```text
clang -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer --target=aarch64-unknown-linux-gnu -Wall -Wextra -nostdlibinc -fno-stack-protector -fno-profile-instr-generate -fno-coverage-mapping -DCOMPILER_RT_HAS_ATOMICS=1 -o <object> -c <source> ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
