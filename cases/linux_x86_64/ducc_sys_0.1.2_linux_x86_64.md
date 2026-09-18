# `ducc-sys` `0.1.2`

Platform: Linux x86_64

## `/work/target/debug/build/ducc-sys-b13a512e38a658e1/out/libduktape.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/duktape`

### Source file examples

* `/work/duktape/duktape.c`
* `/work/duktape/wrapper.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I <include directory> -Wall -Wextra -std=c99 -o <object> -c <source>
```

### Static library construction

```text
ar crs <static library> <object files>
```
