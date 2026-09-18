# `rav1e` `0.7.1`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/rav1e-42dd61522fe100f1/out/librav1e-aarch64.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1`

### Source directories

* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm`
* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64`

### Source file examples

* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64/cdef.S`
* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64/cdef16.S`
* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64/cdef_dist.S`
* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64/ipred.S`
* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64/ipred16.S`

### Compilation

```text
gcc -O1 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I <include directory> -I <include directory> -Wall -Wextra -o <object> -c <source>
```

```text
cc1 -E -lang-asm -quiet -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu <source> -mlittle-endian -mabi=lp64 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -gdwarf-4 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
