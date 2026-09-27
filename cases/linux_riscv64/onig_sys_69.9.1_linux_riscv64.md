# `onig_sys` `69.9.1`

Platform: Linux riscv64

## Submodule

Repository: `https://github.com/iwillspeak/rust-onig`
Crate release commit: `ed05d7ac1a1a138c6d9c46b451b9d9bea0fbe0b1`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `onig_sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `onig_sys/oniguruma`

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
