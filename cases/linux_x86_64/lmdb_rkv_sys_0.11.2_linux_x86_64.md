# `lmdb-rkv-sys` `0.11.2`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/mozilla/lmdb-rs.git`
Crate release commit: `946167603dd6806f3733e18f01a89cee21888468`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `lmdb-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `lmdb-sys/lmdb`

## `/work/target/debug/build/lmdb-rkv-sys-94ce9b72063fc175/out/liblmdb.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/lmdb/libraries/liblmdb`

### Source file examples

* `/work/lmdb/libraries/liblmdb/mdb.c`
* `/work/lmdb/libraries/liblmdb/midl.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -DMDB_IDL_LOGN=16 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
