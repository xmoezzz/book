# `minicov` `0.3.7`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 513873

Build-script executable: `/target/debug/build/minicov-cf5e8875ec696c31/build_script_build-cf5e8875ec696c31`

Working directory: `/tmp/crate-build-ppc64le-c2e7xla7/src/minicov-0.3.7`

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
