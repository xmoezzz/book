# `alloca` `0.4.0`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 457321

Build-script executable: `/target/debug/build/alloca-9996f3817213d50a/build_script_build-9996f3817213d50a`

Working directory: `/tmp/crate-build-aarch64-f0q6md20/src/alloca-0.4.0`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/alloca-144a22e47b49c354/out/libcalloca.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-f0q6md20/src/alloca-0.4.0`

### Source directories

* `/tmp/crate-build-aarch64-f0q6md20/src/alloca-0.4.0`

### Source file examples

* `/tmp/crate-build-aarch64-f0q6md20/src/alloca-0.4.0/alloca.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-f0q6md20/src/alloca-0.4.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/alloca-144a22e47b49c354/out/alloca.o -c alloca.c
```

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -gdwarf-4 -O2 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
