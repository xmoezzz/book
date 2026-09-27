# `zstd-sys` `2.0.15+zstd.1.5.7`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/gyscos/zstd-rs`
Crate release commit: `229054099aa73f7e861762f687d7e07cac1d9b3b`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `zstd-safe/zstd-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `zstd-safe/zstd-sys/zstd`

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
