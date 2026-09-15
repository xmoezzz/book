# `rust-crypto` `0.2.36`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 558869

Build-script executable: `/target/debug/build/rust-crypto-1b57fa267e89186c/build_script_build-1b57fa267e89186c`

Working directory: `/tmp/crate-build-riscv64-ea3do6hr/src/rust-crypto-0.2.36`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/rust-crypto-e585156a5fd910be/out/lib_rust_crypto_helpers.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-ea3do6hr/src/rust-crypto-0.2.36`

### Source directories

* `/tmp/crate-build-riscv64-ea3do6hr/src/rust-crypto-0.2.36/src`

### Source file examples

* `/tmp/crate-build-riscv64-ea3do6hr/src/rust-crypto-0.2.36/src/aesni_helpers.c`
* `/tmp/crate-build-riscv64-ea3do6hr/src/rust-crypto-0.2.36/src/util_helpers.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-ea3do6hr/src/rust-crypto-0.2.36`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/rust-crypto-e585156a5fd910be/out/src/util_helpers.o -c src/util_helpers.c
```

Working directory: `/tmp/crate-build-riscv64-ea3do6hr/src/rust-crypto-0.2.36`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/rust-crypto-e585156a5fd910be/out/src/aesni_helpers.o -c src/aesni_helpers.c
```

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/rust-crypto-e585156a5fd910be/out/src/ -dumpbase <source> -dumpbase-ext .c -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -O0 ...
```

### Static library construction

```text
ar crs <static library> <object files>
```
