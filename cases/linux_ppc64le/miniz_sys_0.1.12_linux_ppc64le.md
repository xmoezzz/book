# `miniz-sys` `0.1.12`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/miniz-sys-a04854fe6813b1a1/out/libminiz.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-wh27ww57/src/miniz-sys-0.1.12`

### Source directories

* `/tmp/crate-build-ppc64le-wh27ww57/src/miniz-sys-0.1.12`

### Source file examples

* `/tmp/crate-build-ppc64le-wh27ww57/src/miniz-sys-0.1.12/miniz.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-wh27ww57/src/miniz-sys-0.1.12`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -w -fvisibility=hidden -DMINIZ_NO_STDIO -DMINIZ_NO_ARCHIVE_APIS -DMINIZ_NO_ARCHIVE_WRITING_APIS -DMINIZ_NO_TIME -DMINIZ_NO_ZLIB_COMPATIBLE_NAMES -o /target/powerpc64le-unknown-linux-gnu/debug/build/miniz-sys-a04854fe6813b1a1/out/db3b6bfb95261072-miniz.o -c miniz.c ...
```

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu -D MINIZ_NO_STDIO -D MINIZ_NO_ARCHIVE_APIS -D MINIZ_NO_ARCHIVE_WRITING_APIS -D MINIZ_NO_TIME -D MINIZ_NO_ZLIB_COMPATIBLE_NAMES <source> -msecure-plt -quiet -dumpbase <source> -m64 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
