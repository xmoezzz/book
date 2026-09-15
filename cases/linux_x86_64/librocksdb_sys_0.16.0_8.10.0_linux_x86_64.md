# `librocksdb-sys` `0.16.0+8.10.0`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 1867494

Build-script executable: `/work/target/debug/build/librocksdb-sys-233cf2a670aea990/build_script_build-233cf2a670aea990`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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
