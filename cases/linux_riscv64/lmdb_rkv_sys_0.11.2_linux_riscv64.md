# `lmdb-rkv-sys` `0.11.2`

Platform: Linux riscv64

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
