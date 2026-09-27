# `lmdb-rkv-sys` `0.11.2`

Platform: Linux ppc64le

## Submodule

Repository: `https://github.com/mozilla/lmdb-rs.git`
Crate release commit: `946167603dd6806f3733e18f01a89cee21888468`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `lmdb-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `lmdb-sys/lmdb`

## `/target/powerpc64le-unknown-linux-gnu/debug/build/lmdb-rkv-sys-cc01287d141daefb/out/liblmdb.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2`

### Source directories

* `/tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb`

### Source file examples

* `/tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/mdb.c`
* `/tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/midl.c`

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu -D MDB_IDL_LOGN=16 <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
