# `librocksdb-sys` `0.16.0+8.10.0`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/rust-rocksdb/rust-rocksdb`
Crate release commit: `b1d8a04778b2aa52cb6e5d3120fec3d0fdc4556c`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `librocksdb-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `librocksdb-sys/rocksdb`
- `librocksdb-sys/snappy`

## `/work/target/debug/build/librocksdb-sys-cf32ea1e96cc1e51/out/librocksdb.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work`

### Source file examples

* `/work/build_version.cc`
* `/work/rocksdb/cache/cache.cc`
* `/work/rocksdb/cache/cache_entry_roles.cc`
* `/work/rocksdb/cache/cache_helpers.cc`
* `/work/rocksdb/cache/cache_key.cc`

### Compilation

```text
c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -I <include directory> -I <include directory> -Wall -Wextra -std=c++17 -Wsign-compare -Wshadow -Wno-unused-parameter -Wno-unused-variable -Woverloaded-virtual -Wnon-virtual-dtor -Wno-missing-field-initializers -Wno-strict-aliasing -Wno-invalid-offsetof -DNDEBUG=1 -DOS_LINUX -DROCKSDB_PLATFORM_POSIX -DROCKSDB_LIB_IO_POSIX -DROCKSDB_SUPPORT_THREAD_LOCAL -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
