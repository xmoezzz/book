# `rav1e` `0.7.1`

Platform: Linux x86_64

## `/work/target/debug/build/rav1e-c63ed9b81fd342dc/out/librav1easm.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src/x86`

### Source file examples

* `/work/src/x86/cdef16_avx2.asm`
* `/work/src/x86/cdef16_avx512.asm`
* `/work/src/x86/cdef16_sse.asm`
* `/work/src/x86/cdef_avx2.asm`
* `/work/src/x86/cdef_avx512.asm`

### Compilation

```text
nasm -felf64 -gdwarf -I<include directory> -I<include directory> <source> -o <object>
```

### Static library construction

```text
ar cq <static library> <object files>
```
