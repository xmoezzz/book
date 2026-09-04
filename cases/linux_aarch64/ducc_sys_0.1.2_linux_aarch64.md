# `ducc-sys` `0.1.2`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/libduktape.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2`

### Source directories

* `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2/duktape`

### Source file examples

* `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2/duktape/duktape.c`
* `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2/duktape/wrapper.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -O0 -Wall -Wextra -std=c99 -ffunction-sections ...
```

### Static library construction

```text
ar crs <static library> <object files>
```
