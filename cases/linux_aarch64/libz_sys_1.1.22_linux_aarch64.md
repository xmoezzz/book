# `libz-sys` `1.1.22`

Platform: Linux aarch64

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

Working directory: `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22`

```text
pkg-config --libs --cflags zlib
```

Working directory: `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22`

```text
pkg-config --modversion zlib
```

## `/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-426cf1505dec65a6/out/lib/libz.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22`

### Source directories

* `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22/src/zlib`

### Source file examples

* `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22/src/zlib/adler32.c`
* `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22/src/zlib/compress.c`
* `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22/src/zlib/crc32.c`
* `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22/src/zlib/deflate.c`
* `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22/src/zlib/gzclose.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu -D STDC -D _LARGEFILE64_SOURCE -D _POSIX_SOURCE <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I <include directory> -fvisibility=hidden -DSTDC -D_LARGEFILE64_SOURCE -D_POSIX_SOURCE -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
