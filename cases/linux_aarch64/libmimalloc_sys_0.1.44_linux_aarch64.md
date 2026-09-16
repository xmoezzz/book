# `libmimalloc-sys` `0.1.44`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/libmimalloc-sys-c88a05e5684fbab9/out/libmimalloc.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-bt_94k32/src/libmimalloc-sys-0.1.44`

### Source directories

* `/tmp/crate-build-aarch64-bt_94k32/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src`

### Source file examples

* `/tmp/crate-build-aarch64-bt_94k32/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src/static.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-bt_94k32/src/libmimalloc-sys-0.1.44`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I c_src/mimalloc/v2/include -I c_src/mimalloc/v2/src -Wall -Wextra -Wno-error=date-time -ftls-model=initial-exec -DMI_DEBUG=0 -o /target/aarch64-unknown-linux-gnu/debug/build/libmimalloc-sys-c88a05e5684fbab9/out/077ae3504b1c7768-static.o -c c_src/mimalloc/v2/src/static.c ...
```

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu -D MI_DEBUG=0 <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -gdwarf-4 -O0 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
