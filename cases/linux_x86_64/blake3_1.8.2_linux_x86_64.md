# `blake3` `1.8.2`

Platform: Linux x86_64

## `/work/target/debug/build/blake3-6b0b720cd86fdbf5/out/libblake3_sse2_sse41_avx2_assembly.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/c`

### Source file examples

* `/work/c/blake3_avx2_x86-64_unix.S`
* `/work/c/blake3_sse2_x86-64_unix.S`
* `/work/c/blake3_sse41_x86-64_unix.S`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -std=c11 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
