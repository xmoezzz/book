# `lmdb-rkv-sys` `0.11.2`

Platform: Linux riscv64

## Submodule

Repository: `https://github.com/mozilla/lmdb-rs.git`
Crate release commit: `946167603dd6806f3733e18f01a89cee21888468`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `lmdb-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `lmdb-sys/lmdb`

## `/target/riscv64gc-unknown-linux-gnu/debug/build/lmdb-rkv-sys-e063bf862ab22450/out/liblmdb.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-kdnjiuqy/src/lmdb-rkv-sys-0.11.2`

### Source directories

* `/tmp/crate-build-riscv64-kdnjiuqy/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb`

### Source file examples

* `/tmp/crate-build-riscv64-kdnjiuqy/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/mdb.c`
* `/tmp/crate-build-riscv64-kdnjiuqy/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/midl.c`

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -D MDB_IDL_LOGN=16 <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/lmdb-rkv-sys-e063bf862ab22450/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
