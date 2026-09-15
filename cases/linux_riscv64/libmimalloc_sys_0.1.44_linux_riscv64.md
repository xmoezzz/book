# `libmimalloc-sys` `0.1.44`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 362790

Build-script executable: `/target/debug/build/libmimalloc-sys-f4207166b664f667/build_script_build-f4207166b664f667`

Working directory: `/tmp/crate-build-riscv64-bwzy2jxq/src/libmimalloc-sys-0.1.44`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/libmimalloc-sys-689d8d8161cb8e80/out/libmimalloc.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-bwzy2jxq/src/libmimalloc-sys-0.1.44`

### Source directories

* `/tmp/crate-build-riscv64-bwzy2jxq/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src`

### Source file examples

* `/tmp/crate-build-riscv64-bwzy2jxq/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src/static.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D MI_DEBUG=0 <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/libmimalloc-sys-689d8d8161cb8e80/out/ -dumpbase <source> -dumpbase-ext .c ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
