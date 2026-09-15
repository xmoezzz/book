# `blake3` `1.8.2`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 163492

Build-script executable: `/target/debug/build/blake3-fea8ad7f6ea67a68/build_script_build-fea8ad7f6ea67a68`

Working directory: `/tmp/crate-build-aarch64-e95vp474/src/blake3-1.8.2`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/blake3-b3d9782f1eec1385/out/libblake3_neon.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-e95vp474/src/blake3-1.8.2`

### Source directories

* `/tmp/crate-build-aarch64-e95vp474/src/blake3-1.8.2/c`

### Source file examples

* `/tmp/crate-build-aarch64-e95vp474/src/blake3-1.8.2/c/blake3_neon.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-e95vp474/src/blake3-1.8.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -std=c11 -o /target/aarch64-unknown-linux-gnu/debug/build/blake3-b3d9782f1eec1385/out/a1edd97dd51cd48d-blake3_neon.o -c c/blake3_neon.c
```

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -gdwarf-4 -O0 -Wall -Wextra -std=c11 -ffunction-sections -fdata-sections -fPIC ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
