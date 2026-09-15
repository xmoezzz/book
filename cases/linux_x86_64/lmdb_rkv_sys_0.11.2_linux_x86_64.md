# `lmdb-rkv-sys` `0.11.2`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 2184023

Build-script executable: `/work/target/debug/build/lmdb-rkv-sys-324c07600afc643d/build_script_build-324c07600afc643d`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/lmdb-rkv-sys-94ce9b72063fc175/out/liblmdb.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/lmdb/libraries/liblmdb`

### Source file examples

* `/work/lmdb/libraries/liblmdb/mdb.c`
* `/work/lmdb/libraries/liblmdb/midl.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -DMDB_IDL_LOGN=16 -o /work/target/debug/build/lmdb-rkv-sys-94ce9b72063fc175/out/b40eeb0d3a911fbe-mdb.o -c /work/lmdb/libraries/liblmdb/mdb.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu -D MDB_IDL_LOGN=16 /work/lmdb/libraries/liblmdb/mdb.c -quiet -dumpdir /work/target/debug/build/lmdb-rkv-sys-94ce9b72063fc175/out/ -dumpbase b40eeb0d3a911fbe-mdb.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -DMDB_IDL_LOGN=16 -o /work/target/debug/build/lmdb-rkv-sys-94ce9b72063fc175/out/b40eeb0d3a911fbe-midl.o -c /work/lmdb/libraries/liblmdb/midl.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu -D MDB_IDL_LOGN=16 /work/lmdb/libraries/liblmdb/midl.c -quiet -dumpdir /work/target/debug/build/lmdb-rkv-sys-94ce9b72063fc175/out/ -dumpbase b40eeb0d3a911fbe-midl.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -DMDB_IDL_LOGN=16 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
