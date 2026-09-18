# `av-scenechange` `0.14.1`

Platform: Linux x86_64

## `/work/target/debug/build/av-scenechange-666c1b2dc1d160c6/out/libavscasm.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src/asm/x86`

### Source file examples

* `/work/src/asm/x86/ipred16_avx2.asm`
* `/work/src/asm/x86/ipred16_avx512.asm`
* `/work/src/asm/x86/ipred16_sse.asm`
* `/work/src/asm/x86/ipred_avx2.asm`
* `/work/src/asm/x86/ipred_avx512.asm`

### Compilation

```text
nasm -felf64 -gdwarf -I<include directory> -I<include directory> <source> -o <object>
```

### Static library construction

```text
ar cq <static library> <object files>
```
