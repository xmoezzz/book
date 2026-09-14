# `ring` `0.17.14`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1796180

Build-script executable: `/work/target/debug/build/ring-db2df25711cce320/build_script_build-db2df25711cce320`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/ring-92e8a52839e59707/out/libring_core_0_17_14_.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work`

### Source file examples

* `/work/crypto/cpu_intel.c`
* `/work/crypto/crypto.c`
* `/work/crypto/curve25519/curve25519.c`
* `/work/crypto/curve25519/curve25519_64_adx.c`
* `/work/crypto/fipsmodule/aes/aes_nohw.c`

### Source preparation

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/include -I /work/pregenerated -imultiarch x86_64-linux-gnu -dD -D NDEBUG /work/crypto/curve25519/curve25519.c -quiet -dumpdir /work/target/debug/build/ring-92e8a52839e59707/out/ -dumpbase 25ac62e5b3c53843-curve25519.c -dumpbase-ext .c -m64 ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/include -I /work/pregenerated -imultiarch x86_64-linux-gnu -dD -D NDEBUG /work/crypto/fipsmodule/aes/aes_nohw.c -quiet -dumpdir /work/target/debug/build/ring-92e8a52839e59707/out/ -dumpbase 0bbbd18bda93c05b-aes_nohw.c -dumpbase-ext .c -m64 ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/include -I /work/pregenerated -imultiarch x86_64-linux-gnu -dD -D NDEBUG /work/crypto/fipsmodule/bn/montgomery.c -quiet -dumpdir /work/target/debug/build/ring-92e8a52839e59707/out/ -dumpbase 00c879ee3285a50d-montgomery.c -dumpbase-ext .c -m64 ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/include -I /work/pregenerated -imultiarch x86_64-linux-gnu -dD -D NDEBUG /work/crypto/fipsmodule/bn/montgomery_inv.c -quiet -dumpdir /work/target/debug/build/ring-92e8a52839e59707/out/ -dumpbase 00c879ee3285a50d-montgomery_inv.c -dumpbase-ext .c -m64 ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/include -I /work/pregenerated -imultiarch x86_64-linux-gnu -dD -D NDEBUG /work/crypto/fipsmodule/ec/ecp_nistz.c -quiet -dumpdir /work/target/debug/build/ring-92e8a52839e59707/out/ -dumpbase a0330e891e733f4e-ecp_nistz.c -dumpbase-ext .c -m64 ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion -Wmissing-field-initializers -Wmissing-include-dirs -Wnested-externs -Wredundant-decls -Wshadow -Wsign-compare -Wsign-conversion -Wstrict-prototypes -Wundef -Wuninitialized -g3 -DNDEBUG -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```

## `/work/target/debug/build/ring-92e8a52839e59707/out/libring_core_0_17_14__test.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/crypto`

### Source file examples

* `/work/crypto/constant_time_test.c`

### Source preparation

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/include -I /work/pregenerated -imultiarch x86_64-linux-gnu -dD -D NDEBUG /work/crypto/constant_time_test.c -quiet -dumpdir /work/target/debug/build/ring-92e8a52839e59707/out/ -dumpbase a4019cc0736b0423-constant_time_test.c -dumpbase-ext .c -m64 ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion -Wmissing-field-initializers -Wmissing-include-dirs -Wnested-externs -Wredundant-decls -Wshadow -Wsign-compare -Wsign-conversion -Wstrict-prototypes -Wundef -Wuninitialized -g3 -DNDEBUG -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
