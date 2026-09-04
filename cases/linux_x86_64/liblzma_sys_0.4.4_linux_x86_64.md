# `liblzma-sys` `0.4.4`

Platform: Linux x86_64

## `/work/target/debug/build/liblzma-sys-989e8346251acdd2/out/liblzma.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/xz/src`

### Source file examples

* `/work/xz/src/common/tuklib_cpucores.c`
* `/work/xz/src/common/tuklib_physmem.c`
* `/work/xz/src/liblzma/check/check.c`
* `/work/xz/src/liblzma/check/crc32_fast.c`
* `/work/xz/src/liblzma/check/crc64_fast.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -Wall -Wextra -std=c99 -DHAVE_CONFIG_H=1 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
