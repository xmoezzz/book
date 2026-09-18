# `libmimalloc-sys` `0.1.44`

Platform: Linux x86_64

## `/work/target/debug/build/libmimalloc-sys-7a37162def3796f8/out/libmimalloc.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/c_src/mimalloc/v2/src`

### Source file examples

* `/work/c_src/mimalloc/v2/src/static.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -Wall -Wextra -Wno-error=date-time -DMI_DEBUG=0 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
