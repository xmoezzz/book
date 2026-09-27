# `librocksdb-sys` `0.16.0+8.10.0`

Platform: Windows x86_64

## Submodule

Repository: `https://github.com/rust-rocksdb/rust-rocksdb`
Crate release commit: `b1d8a04778b2aa52cb6e5d3120fec3d0fdc4556c`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `librocksdb-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `librocksdb-sys/rocksdb`
- `librocksdb-sys/snappy`

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-sulb1mq1/src/librocksdb-sys-0.16.0+8.10.0/target/debug/build/librocksdb-sys-f3dfc4263f902b6b/out/librocksdb.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-sulb1mq1/src/librocksdb-sys-0.16.0+8.10.0`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-sulb1mq1/src/librocksdb-sys-0.16.0+8.10.0`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-sulb1mq1/src/librocksdb-sys-0.16.0+8.10.0/build_version.cc`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-sulb1mq1/src/librocksdb-sys-0.16.0+8.10.0/rocksdb/cache/cache.cc`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-sulb1mq1/src/librocksdb-sys-0.16.0+8.10.0/rocksdb/cache/cache_entry_roles.cc`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-sulb1mq1/src/librocksdb-sys-0.16.0+8.10.0/rocksdb/cache/cache_helpers.cc`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-sulb1mq1/src/librocksdb-sys-0.16.0+8.10.0/rocksdb/cache/cache_key.cc`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -I <include directory> -I <include directory> -I <include directory> -W4 -EHsc -std:c++17 -DNDEBUG=1 -DDWIN32 -DOS_WIN -D_MBCS -DWIN64 -DNOMINMAX -DROCKSDB_WINDOWS_UTF8_FILENAMES -DROCKSDB_SUPPORT_THREAD_LOCAL <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
