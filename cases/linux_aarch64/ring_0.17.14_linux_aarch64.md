# `ring` `0.17.14`

Platform: Linux aarch64

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
