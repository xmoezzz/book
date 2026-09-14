# `blst` `0.3.16`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1251488

Build-script executable: `/target/debug/build/blst-0fe97681e9975598/build_script_build-0fe97681e9975598`

Working directory: `/tmp/crate-build-riscv64-84usivvg/src/blst-0.3.16`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/blst-3351224bbbe670bb/out/libblst.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-84usivvg/src/blst-0.3.16`

### Source directories

* `/tmp/crate-build-riscv64-84usivvg/src/blst-0.3.16/blst/src`

### Source file examples

* `/tmp/crate-build-riscv64-84usivvg/src/blst-0.3.16/blst/src/server.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-84usivvg/src/blst-0.3.16`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -fno-builtin -Wno-unused-function -Wno-unused-command-line-argument -D__BLST_NO_ASM__ -o /target/riscv64gc-unknown-linux-gnu/debug/build/blst-3351224bbbe670bb/out/3ce72ea41a6346fd-server.o -c /tmp/crate-build-riscv64-84usivvg/src/blst-0.3.16/blst/src/server.c
```

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -D __BLST_NO_ASM__ <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/blst-3351224bbbe670bb/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
