# `ring` `0.17.14`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 30673

Build-script executable: `/target/debug/build/ring-19b641f5c8ef9c4a/build_script_build-19b641f5c8ef9c4a`

Working directory: `/tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/libring_core_0_17_14_.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14`

### Source directories

* `/tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14`

### Source file examples

* `/tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/curve25519/curve25519.c`
* `/tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/fipsmodule/aes/aes_nohw.c`
* `/tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/fipsmodule/bn/montgomery.c`
* `/tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/fipsmodule/bn/montgomery_inv.c`
* `/tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/fipsmodule/ec/ecp_nistz.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu -dD -D NDEBUG <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -gdwarf-4 ...
```

```text
cc1 -E -lang-asm -quiet -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu -dD -D NDEBUG <source> -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...
```

### Static library construction

```text
ar cq <static library> <object files>
```

## `/target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/libring_core_0_17_14__test.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14`

### Source directories

* `/tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto`

### Source file examples

* `/tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/constant_time_test.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu -dD -D NDEBUG <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -gdwarf-4 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
