# `rust-crypto` `0.2.36`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 558870

Build-script executable: `/target/debug/build/rust-crypto-1b57fa267e89186c/build_script_build-1b57fa267e89186c`

Working directory: `/tmp/crate-build-ppc64le-3ya1h62o/src/rust-crypto-0.2.36`

Full linker command: retained in the raw case.

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/rust-crypto-b5420c5e84710682/out/lib_rust_crypto_helpers.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-3ya1h62o/src/rust-crypto-0.2.36`

### Source directories

* `/tmp/crate-build-ppc64le-3ya1h62o/src/rust-crypto-0.2.36/src`

### Source file examples

* `/tmp/crate-build-ppc64le-3ya1h62o/src/rust-crypto-0.2.36/src/aesni_helpers.c`
* `/tmp/crate-build-ppc64le-3ya1h62o/src/rust-crypto-0.2.36/src/util_helpers.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-3ya1h62o/src/rust-crypto-0.2.36`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/rust-crypto-b5420c5e84710682/out/src/util_helpers.o -c src/util_helpers.c
```

Working directory: `/tmp/crate-build-ppc64le-3ya1h62o/src/rust-crypto-0.2.36`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/rust-crypto-b5420c5e84710682/out/src/aesni_helpers.o -c src/aesni_helpers.c
```

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -O0 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...
```

### Static library construction

```text
ar crs <static library> <object files>
```
