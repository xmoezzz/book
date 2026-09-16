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

### Source preparation

Working directory: `/work`

```text
/usr/bin/nasm -felf64 -gdwarf -I/work/target/debug/build/av-scenechange-666c1b2dc1d160c6/out/ -Isrc/ /work/src/asm/x86/ipred16_avx2.asm -o /work/target/debug/build/av-scenechange-666c1b2dc1d160c6/out/ipred16_avx2.o
```

Working directory: `/work`

```text
/usr/bin/nasm -felf64 -gdwarf -I/work/target/debug/build/av-scenechange-666c1b2dc1d160c6/out/ -Isrc/ /work/src/asm/x86/mc_sse.asm -o /work/target/debug/build/av-scenechange-666c1b2dc1d160c6/out/mc_sse.o
```

Working directory: `/work`

```text
/usr/bin/nasm -felf64 -gdwarf -I/work/target/debug/build/av-scenechange-666c1b2dc1d160c6/out/ -Isrc/ /work/src/asm/x86/ipred_avx2.asm -o /work/target/debug/build/av-scenechange-666c1b2dc1d160c6/out/ipred_avx2.o
```

Working directory: `/work`

```text
/usr/bin/nasm -felf64 -gdwarf -I/work/target/debug/build/av-scenechange-666c1b2dc1d160c6/out/ -Isrc/ /work/src/asm/x86/ipred_sse.asm -o /work/target/debug/build/av-scenechange-666c1b2dc1d160c6/out/ipred_sse.o
```

Working directory: `/work`

```text
/usr/bin/nasm -felf64 -gdwarf -I/work/target/debug/build/av-scenechange-666c1b2dc1d160c6/out/ -Isrc/ /work/src/asm/x86/mc_avx2.asm -o /work/target/debug/build/av-scenechange-666c1b2dc1d160c6/out/mc_avx2.o
```

### Compilation

```text
nasm -felf64 -gdwarf -I<include directory> -I<include directory> <source> -o <object>
```

### Static library construction

```text
ar cq <static library> <object files>
```
