# `sys-info` `0.9.1`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 200199

Build-script executable: `/target/debug/build/sys-info-c76387d5ac2d2e2b/build_script_build-c76387d5ac2d2e2b`

Working directory: `/tmp/crate-build-aarch64-yk7f0hk6/src/sys-info-0.9.1`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/sys-info-a0f0a44cc67689b8/out/libinfo.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-yk7f0hk6/src/sys-info-0.9.1`

### Source directories

* `/tmp/crate-build-aarch64-yk7f0hk6/src/sys-info-0.9.1/c`

### Source file examples

* `/tmp/crate-build-aarch64-yk7f0hk6/src/sys-info-0.9.1/c/linux.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-yk7f0hk6/src/sys-info-0.9.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/sys-info-a0f0a44cc67689b8/out/a1edd97dd51cd48d-linux.o -c c/linux.c
```

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
