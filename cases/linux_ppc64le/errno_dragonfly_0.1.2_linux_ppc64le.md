# `errno-dragonfly` `0.1.2`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 136677

Build-script executable: `/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395`

Working directory: `/tmp/crate-build-ppc64le-2lth2o0u/src/errno-dragonfly-0.1.2`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/liberrno.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-2lth2o0u/src/errno-dragonfly-0.1.2`

### Source directories

* `/tmp/crate-build-ppc64le-2lth2o0u/src/errno-dragonfly-0.1.2/src`

### Source file examples

* `/tmp/crate-build-ppc64le-2lth2o0u/src/errno-dragonfly-0.1.2/src/errno.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-2lth2o0u/src/errno-dragonfly-0.1.2`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/ea708c7824d36062-errno.o -c src/errno.c
```

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
