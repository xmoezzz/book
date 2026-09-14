# `lmdb-rkv-sys` `0.11.2`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1161540

Build-script executable: `/target/debug/build/lmdb-rkv-sys-386b6c2af8de88a6/build_script_build-386b6c2af8de88a6`

Working directory: `/tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2`

Full linker command: retained in the raw case.

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/lmdb-rkv-sys-cc01287d141daefb/out/liblmdb.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2`

### Source directories

* `/tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb`

### Source file examples

* `/tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/mdb.c`
* `/tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/midl.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -Wno-unused-parameter -Wbad-function-cast -Wuninitialized -DMDB_IDL_LOGN=16 -o /target/powerpc64le-unknown-linux-gnu/debug/build/lmdb-rkv-sys-cc01287d141daefb/out/b40eeb0d3a911fbe-mdb.o -c /tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/mdb.c
```

Working directory: `/tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -Wno-unused-parameter -Wbad-function-cast -Wuninitialized -DMDB_IDL_LOGN=16 -o /target/powerpc64le-unknown-linux-gnu/debug/build/lmdb-rkv-sys-cc01287d141daefb/out/b40eeb0d3a911fbe-midl.o -c /tmp/crate-build-ppc64le-lplf01xz/src/lmdb-rkv-sys-0.11.2/lmdb/libraries/liblmdb/midl.c
```

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu -D MDB_IDL_LOGN=16 <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
