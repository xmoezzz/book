# `libz-sys` `1.1.22`

Platform: Linux ppc64le

## Submodule

Repository: `https://github.com/rust-lang/libz-sys`
Crate release commit: `7a4e6d74ee26c954ee9c512b0ee7bad81b7b5e06`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `src/zlib`
- `src/zlib-ng`

## Build-level coding evidence

### pkg-config / pkgconf

Working directory: `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22`

```text
pkg-config --libs --cflags zlib
```

Working directory: `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22`

```text
pkg-config --modversion zlib
```

## `/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e5427401654749bb/out/lib/libz.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22`

### Source directories

* `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22/src/zlib`

### Source file examples

* `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22/src/zlib/adler32.c`
* `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22/src/zlib/compress.c`
* `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22/src/zlib/crc32.c`
* `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22/src/zlib/deflate.c`
* `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22/src/zlib/gzclose.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu -D STDC -D _LARGEFILE64_SOURCE -D _POSIX_SOURCE <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
