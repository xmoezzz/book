# `libz-sys` `1.1.22`

Platform: Linux ppc64le

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

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 190889

Build-script executable: `/target/debug/build/libz-sys-a339e721195e716e/build_script_build-a339e721195e716e`

Working directory: `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22`

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

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src/zlib -fvisibility=hidden -DSTDC -D_LARGEFILE64_SOURCE -D_POSIX_SOURCE -o /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e5427401654749bb/out/lib/0dc752f03a07a721-adler32.o -c src/zlib/adler32.c
```

Working directory: `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src/zlib -fvisibility=hidden -DSTDC -D_LARGEFILE64_SOURCE -D_POSIX_SOURCE -o /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e5427401654749bb/out/lib/0dc752f03a07a721-compress.o -c src/zlib/compress.c
```

Working directory: `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src/zlib -fvisibility=hidden -DSTDC -D_LARGEFILE64_SOURCE -D_POSIX_SOURCE -o /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e5427401654749bb/out/lib/0dc752f03a07a721-crc32.o -c src/zlib/crc32.c
```

Working directory: `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src/zlib -fvisibility=hidden -DSTDC -D_LARGEFILE64_SOURCE -D_POSIX_SOURCE -o /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e5427401654749bb/out/lib/0dc752f03a07a721-deflate.o -c src/zlib/deflate.c
```

Working directory: `/tmp/crate-build-ppc64le-dk6tgpvm/src/libz-sys-1.1.22`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src/zlib -fvisibility=hidden -DSTDC -D_LARGEFILE64_SOURCE -D_POSIX_SOURCE -o /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e5427401654749bb/out/lib/0dc752f03a07a721-infback.o -c src/zlib/infback.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu -D STDC -D _LARGEFILE64_SOURCE -D _POSIX_SOURCE <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
