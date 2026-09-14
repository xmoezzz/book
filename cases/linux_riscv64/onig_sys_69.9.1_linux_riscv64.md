# `onig_sys` `69.9.1`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 223773

Build-script executable: `/target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a`

Working directory: `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out/libonig.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1`

### Source directories

* `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1/oniguruma/src`

### Source file examples

* `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1/oniguruma/src/ascii.c`
* `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1/oniguruma/src/onig_init.c`
* `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1/oniguruma/src/regcomp.c`
* `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1/oniguruma/src/regenc.c`
* `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1/oniguruma/src/regerror.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out/a445302c6d3dcb51-regexec.o -c oniguruma/src/regexec.c ...
```

Working directory: `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out/a445302c6d3dcb51-regerror.o -c oniguruma/src/regerror.c ...
```

Working directory: `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out/a445302c6d3dcb51-regparse.o -c oniguruma/src/regparse.c ...
```

Working directory: `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out/a445302c6d3dcb51-regext.o -c oniguruma/src/regext.c ...
```

Working directory: `/tmp/crate-build-riscv64-229vek2j/src/onig_sys-69.9.1`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out/a445302c6d3dcb51-regcomp.o -c oniguruma/src/regcomp.c ...
```

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D HAVE_UNISTD_H=1 -D HAVE_SYS_TYPES_H=1 -D HAVE_SYS_TIME_H=1 <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/onig_sys-9c68e8be589e44ec/out/ ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I <include directory> -I <include directory> -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o <object> -c <source> ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
