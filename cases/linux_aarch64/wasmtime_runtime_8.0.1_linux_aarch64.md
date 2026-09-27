# `wasmtime-runtime` `8.0.1`

Platform: Linux aarch64

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

## `/target/aarch64-unknown-linux-gnu/debug/build/wasmtime-runtime-54c203e6228eed37/out/libwasmtime-helpers.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-axwoxy51/src/wasmtime-runtime-8.0.1`

### Source directories

* `/tmp/crate-build-aarch64-axwoxy51/src/wasmtime-runtime-8.0.1/src`

### Source file examples

* `/tmp/crate-build-aarch64-axwoxy51/src/wasmtime-runtime-8.0.1/src/helpers.c`

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_aarch64 <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
