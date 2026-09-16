# `minicov` `0.3.7`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/minicov-1dd553365fac27c5/out/libllvm_profiler_runtime.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-c2e7xla7/src/minicov-0.3.7`

### Source directories

* `/tmp/crate-build-ppc64le-c2e7xla7/src/minicov-0.3.7/c`

### Source file examples

* `/tmp/crate-build-ppc64le-c2e7xla7/src/minicov-0.3.7/c/InstrProfiling.c`
* `/tmp/crate-build-ppc64le-c2e7xla7/src/minicov-0.3.7/c/InstrProfilingBuffer.c`
* `/tmp/crate-build-ppc64le-c2e7xla7/src/minicov-0.3.7/c/InstrProfilingInternal.c`
* `/tmp/crate-build-ppc64le-c2e7xla7/src/minicov-0.3.7/c/InstrProfilingMerge.c`
* `/tmp/crate-build-ppc64le-c2e7xla7/src/minicov-0.3.7/c/InstrProfilingPlatformLinux.c`

### Compilation

```text
clang -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 --target=powerpc64le-unknown-linux-gnu -Wall -Wextra -nostdlibinc -fno-stack-protector -fno-profile-instr-generate -fno-coverage-mapping -DCOMPILER_RT_HAS_ATOMICS=1 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
