# `libz-sys` `1.1.22`

Platform: Linux aarch64

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

### Source preparation

Working directory: `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I src/zlib -fvisibility=hidden -DSTDC -D_LARGEFILE64_SOURCE -D_POSIX_SOURCE -o /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-426cf1505dec65a6/out/lib/0dc752f03a07a721-adler32.o -c src/zlib/adler32.c
```

Working directory: `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I src/zlib -fvisibility=hidden -DSTDC -D_LARGEFILE64_SOURCE -D_POSIX_SOURCE -o /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-426cf1505dec65a6/out/lib/0dc752f03a07a721-compress.o -c src/zlib/compress.c
```

Working directory: `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I src/zlib -fvisibility=hidden -DSTDC -D_LARGEFILE64_SOURCE -D_POSIX_SOURCE -o /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-426cf1505dec65a6/out/lib/0dc752f03a07a721-crc32.o -c src/zlib/crc32.c
```

Working directory: `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I src/zlib -fvisibility=hidden -DSTDC -D_LARGEFILE64_SOURCE -D_POSIX_SOURCE -o /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-426cf1505dec65a6/out/lib/0dc752f03a07a721-deflate.o -c src/zlib/deflate.c
```

Working directory: `/tmp/crate-build-aarch64-ijugia1j/src/libz-sys-1.1.22`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I src/zlib -fvisibility=hidden -DSTDC -D_LARGEFILE64_SOURCE -D_POSIX_SOURCE -o /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-426cf1505dec65a6/out/lib/0dc752f03a07a721-infback.o -c src/zlib/infback.c
```

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
