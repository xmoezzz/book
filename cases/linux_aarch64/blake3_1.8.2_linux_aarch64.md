# `blake3` `1.8.2`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/blake3-b3d9782f1eec1385/out/libblake3_neon.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-e95vp474/src/blake3-1.8.2`

### Source directories

* `/tmp/crate-build-aarch64-e95vp474/src/blake3-1.8.2/c`

### Source file examples

* `/tmp/crate-build-aarch64-e95vp474/src/blake3-1.8.2/c/blake3_neon.c`

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -gdwarf-4 -O0 -Wall -Wextra -std=c11 -ffunction-sections -fdata-sections -fPIC ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
