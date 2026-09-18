# `lmdb-rkv-sys` `0.11.2`

Platform: Linux x86_64

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
