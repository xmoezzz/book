# `wasmtime-runtime` `8.0.1`

Platform: Linux riscv64

## Submodule

Repository: `https://github.com/bytecodealliance/wasmtime`
Crate release commit: `207cd1ce15ecc504dafaec490c5eae801cac4691`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `crates/runtime`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `crates/c-api/wasm-c-api`
- `crates/wasi-common/WASI`
- `crates/wasi-crypto/spec`
- `crates/wasi-nn/spec`
- `tests/spec_testsuite`
- `tests/wasi_testsuite/wasi-threads`

## `/target/riscv64gc-unknown-linux-gnu/debug/build/wasmtime-runtime-bf12678ed4790af9/out/libwasmtime-helpers.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-a7fz7ila/src/wasmtime-runtime-8.0.1`

### Source directories

* `/tmp/crate-build-riscv64-a7fz7ila/src/wasmtime-runtime-8.0.1/src`

### Source file examples

* `/tmp/crate-build-riscv64-a7fz7ila/src/wasmtime-runtime-8.0.1/src/helpers.c`

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_riscv64 <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/wasmtime-runtime-bf12678ed4790af9/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
