# `liblzma-sys` `0.4.4`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 1916798

Build-script executable: `/work/target/debug/build/liblzma-sys-70d6999b8d3207cf/build_script_build-70d6999b8d3207cf`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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
