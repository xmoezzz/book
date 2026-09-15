# `sys-info` `0.9.1`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 199811

Build-script executable: `/target/debug/build/sys-info-c76387d5ac2d2e2b/build_script_build-c76387d5ac2d2e2b`

Working directory: `/tmp/crate-build-riscv64-zxe18_5n/src/sys-info-0.9.1`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/sys-info-13b8bdd4f9a823ed/out/libinfo.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-zxe18_5n/src/sys-info-0.9.1`

### Source directories

* `/tmp/crate-build-riscv64-zxe18_5n/src/sys-info-0.9.1/c`

### Source file examples

* `/tmp/crate-build-riscv64-zxe18_5n/src/sys-info-0.9.1/c/linux.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-zxe18_5n/src/sys-info-0.9.1`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/sys-info-13b8bdd4f9a823ed/out/a1edd97dd51cd48d-linux.o -c c/linux.c
```

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/sys-info-13b8bdd4f9a823ed/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
