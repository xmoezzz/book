# `lmdb-rkv-sys` `0.11.2`

Platform: Linux ppc64le

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
