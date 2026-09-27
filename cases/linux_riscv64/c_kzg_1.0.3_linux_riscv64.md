# `c-kzg` `1.0.3`

Platform: Linux riscv64

## Submodule

Repository: `https://github.com/ethereum/c-kzg-4844`
Crate release commit: `75d569b16cb2e17a33484af0f03ec633cba3b582`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `blst`

## `/target/riscv64gc-unknown-linux-gnu/debug/build/c-kzg-5d17959e8d535f25/out/libckzg.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3`

### Source directories

* `/tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3/src`

### Source file examples

* `/tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3/src/c_kzg_4844.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/c-kzg-5d17959e8d535f25/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
