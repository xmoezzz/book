# `sha2-asm` `0.6.4`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/libsha256.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4`

### Source directories

* `/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4/src`

### Source file examples

* `/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4/src/sha256_aarch64.S`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -march=armv8-a+crypto -c -o /target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o -c src/sha256_aarch64.S
```

### Compilation

```text
cc1 -E -lang-asm -quiet -imultiarch aarch64-linux-gnu <source> -march=armv8-a+crypto -mlittle-endian -mabi=lp64 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -g -gdwarf-4 -fworking-directory -O0 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
