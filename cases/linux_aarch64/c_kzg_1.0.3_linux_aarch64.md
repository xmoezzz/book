# `c-kzg` `1.0.3`

Platform: Linux aarch64

## Submodule

Repository: `https://github.com/ethereum/c-kzg-4844`
Crate release commit: `75d569b16cb2e17a33484af0f03ec633cba3b582`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `blst`

## `/target/aarch64-unknown-linux-gnu/debug/build/c-kzg-1599ee71ecaeb2bb/out/libckzg.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3`

### Source directories

* `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3/src`

### Source file examples

* `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3/src/c_kzg_4844.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -w -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
