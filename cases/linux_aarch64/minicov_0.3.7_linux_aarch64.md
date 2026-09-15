# `minicov` `0.3.7`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 512243

Build-script executable: `/target/debug/build/minicov-cf5e8875ec696c31/build_script_build-cf5e8875ec696c31`

Working directory: `/tmp/crate-build-aarch64-tr935jbb/src/minicov-0.3.7`

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
clang -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer --target=aarch64-unknown-linux-gnu -Wall -Wextra -nostdlibinc -fno-stack-protector -fno-profile-instr-generate -fno-coverage-mapping -DCOMPILER_RT_HAS_ATOMICS=1 -o <object> -c <source> ...
```

```text
clang -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer --target=aarch64-unknown-linux-gnu -Wall -Wextra -nostdlibinc -fno-stack-protector -fno-profile-instr-generate -fno-coverage-mapping -DCOMPILER_RT_HAS_ATOMICS=1 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
