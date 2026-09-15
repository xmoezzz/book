# `lmdb-rkv-sys` `0.11.2`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 1160621

Build-script executable: `/target/debug/build/lmdb-rkv-sys-386b6c2af8de88a6/build_script_build-386b6c2af8de88a6`

Working directory: `/tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/aarch64-unknown-linux-gnu/debug/build/lmdb-rkv-sys-b48e465e751f7a06/out/liblmdb.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2`

### Source directories

* `/tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb`

### Source file examples

* `/tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/mdb.c`
* `/tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/midl.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -Wno-unused-parameter -Wbad-function-cast -Wuninitialized -DMDB_IDL_LOGN=16 -o /target/aarch64-unknown-linux-gnu/debug/build/lmdb-rkv-sys-b48e465e751f7a06/out/b40eeb0d3a911fbe-mdb.o -c /tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/mdb.c
```

Working directory: `/tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -Wno-unused-parameter -Wbad-function-cast -Wuninitialized -DMDB_IDL_LOGN=16 -o /target/aarch64-unknown-linux-gnu/debug/build/lmdb-rkv-sys-b48e465e751f7a06/out/b40eeb0d3a911fbe-midl.o -c /tmp/crate-build-aarch64-ft6h7zlr/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/midl.c
```

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu -D MDB_IDL_LOGN=16 <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-parameter ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
