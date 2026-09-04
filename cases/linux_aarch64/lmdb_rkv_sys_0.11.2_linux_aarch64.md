# `lmdb-rkv-sys` `0.11.2`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/lmdb-rkv-sys-b48e465e751f7a06/out/liblmdb.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2`

### Source directories

* `/tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb`

### Source file examples

* `/tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/mdb.c`
* `/tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/midl.c`

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu -D MDB_IDL_LOGN=16 <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-parameter ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
