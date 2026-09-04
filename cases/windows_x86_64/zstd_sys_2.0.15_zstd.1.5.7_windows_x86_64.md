# `zstd-sys` `2.0.15+zstd.1.5.7`

Platform: Windows x86_64

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7/target/debug/build/zstd-sys-68c51da2414ecbb3/out/libzstd.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7/zstd/lib/common`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7/zstd/lib/compress`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7/zstd/lib/decompress`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7/zstd/lib/dictBuilder`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7/zstd/lib/legacy`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7/zstd/lib/common/debug.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7/zstd/lib/common/entropy_common.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7/zstd/lib/common/error_private.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7/zstd/lib/common/fse_decompress.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-lsgmupgn/src/zstd-sys-2.0.15+zstd.1.5.7/zstd/lib/common/pool.c`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -I <include directory> -I <include directory> -fvisibility=hidden -DZSTD_DISABLE_ASM= -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= -DZSTDLIB_VISIBILITY= -DZDICTLIB_VISIBILITY= -DZSTDERRORLIB_VISIBILITY= -DZSTD_LEGACY_SUPPORT=1 <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
