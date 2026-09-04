# `zstd-sys` `2.0.15+zstd.1.5.7`

Platform: Linux x86_64

## `/work/target/debug/build/zstd-sys-09d50964787a6dfd/out/libzstd.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/zstd/lib/common`
* `/work/zstd/lib/compress`
* `/work/zstd/lib/decompress`
* `/work/zstd/lib/dictBuilder`
* `/work/zstd/lib/legacy`

### Source file examples

* `/work/zstd/lib/common/debug.c`
* `/work/zstd/lib/common/entropy_common.c`
* `/work/zstd/lib/common/error_private.c`
* `/work/zstd/lib/common/fse_decompress.c`
* `/work/zstd/lib/common/pool.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -I <include directory> -fvisibility=hidden -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= -DZSTDLIB_VISIBILITY= -DZDICTLIB_VISIBILITY= -DZSTDERRORLIB_VISIBILITY= -DZSTD_LEGACY_SUPPORT=1 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
