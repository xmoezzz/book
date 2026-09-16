# `ring` `0.17.14`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/libring_core_0_17_14_.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14`

### Source directories

* `/tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto`

### Source file examples

* `/tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/curve25519/curve25519.c`
* `/tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/aes/aes_nohw.c`
* `/tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/bn/montgomery.c`
* `/tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/bn/montgomery_inv.c`
* `/tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/ec/ecp_nistz.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> ...
```

### Static library construction

```text
ar cq <static library> <object files>
```

## `/target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/libring_core_0_17_14__test.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14`

### Source directories

* `/tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto`

### Source file examples

* `/tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/constant_time_test.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
