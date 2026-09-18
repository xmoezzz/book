# `ducc-sys` `0.1.2`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/libduktape.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2`

### Source directories

* `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2/duktape`

### Source file examples

* `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2/duktape/duktape.c`
* `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2/duktape/wrapper.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -O0 -Wall -Wextra -std=c99 ...
```

### Static library construction

```text
ar crs <static library> <object files>
```
