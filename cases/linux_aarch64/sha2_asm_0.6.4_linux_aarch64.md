# `sha2-asm` `0.6.4`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 412082

Build-script executable: `/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186`

Working directory: `/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

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
