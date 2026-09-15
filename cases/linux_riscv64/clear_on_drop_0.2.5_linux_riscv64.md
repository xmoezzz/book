# `clear_on_drop` `0.2.5`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 876192

Build-script executable: `/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058`

Working directory: `/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5`

### Source directories

* `/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5/src`

### Source file examples

* `/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5/src/hide.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o -c src/hide.c
```

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
