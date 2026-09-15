# `ring` `0.17.14`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 30667

Build-script executable: `/target/debug/build/ring-19b641f5c8ef9c4a/build_script_build-19b641f5c8ef9c4a`

Working directory: `/tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/libring_core_0_17_14_.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14`

### Source directories

* `/tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto`

### Source file examples

* `/tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/curve25519/curve25519.c`
* `/tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/fipsmodule/aes/aes_nohw.c`
* `/tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/fipsmodule/bn/montgomery.c`
* `/tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/fipsmodule/bn/montgomery_inv.c`
* `/tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/fipsmodule/ec/ecp_nistz.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -dD -D NDEBUG <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/ -dumpbase <source> -dumpbase-ext ...
```

### Static library construction

```text
ar cq <static library> <object files>
```

## `/target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/libring_core_0_17_14__test.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14`

### Source directories

* `/tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto`

### Source file examples

* `/tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/constant_time_test.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -dD -D NDEBUG <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/ -dumpbase <source> -dumpbase-ext ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
