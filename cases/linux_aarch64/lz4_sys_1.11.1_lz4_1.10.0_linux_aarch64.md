# `lz4-sys` `1.11.1+lz4-1.10.0`

Platform: Linux aarch64

## Submodule

Repository: `https://github.com/10xGenomics/lz4-rs`
Crate release commit: `5f52707d2e9b3c7f6a1a3e95180c00e7a6204d21`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `lz4-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `lz4-sys/liblz4`

## `/target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/liblz4.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0`

### Source directories

* `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib`

### Source file examples

* `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4.c`
* `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4frame.c`
* `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4hc.c`
* `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/xxhash.c`

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O3 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
