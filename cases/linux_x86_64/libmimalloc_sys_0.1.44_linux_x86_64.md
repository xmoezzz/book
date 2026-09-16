# `libmimalloc-sys` `0.1.44`

Platform: Linux x86_64

## `/work/target/debug/build/libmimalloc-sys-7a37162def3796f8/out/libmimalloc.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/c_src/mimalloc/v2/src`

### Source file examples

* `/work/c_src/mimalloc/v2/src/static.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I c_src/mimalloc/v2/include -I c_src/mimalloc/v2/src -Wall -Wextra -Wno-error=date-time -DMI_DEBUG=0 -o /work/target/debug/build/libmimalloc-sys-7a37162def3796f8/out/077ae3504b1c7768-static.o -c c_src/mimalloc/v2/src/static.c ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I c_src/mimalloc/v2/include -I c_src/mimalloc/v2/src -imultiarch x86_64-linux-gnu -D MI_DEBUG=0 c_src/mimalloc/v2/src/static.c -quiet -dumpdir /work/target/debug/build/libmimalloc-sys-7a37162def3796f8/out/ -dumpbase 077ae3504b1c7768-static.c -dumpbase-ext .c -m64 -mtune=generic ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -Wall -Wextra -Wno-error=date-time -DMI_DEBUG=0 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
