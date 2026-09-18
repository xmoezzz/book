# `lcms2-sys` `4.0.5`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/lcms2-sys-5fede971eb0990c2/out/liblcms2.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5`

### Source directories

* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src`

### Source file examples

* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src/cmsalpha.c`
* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src/cmscam02.c`
* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src/cmscgats.c`
* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src/cmscnvrt.c`
* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src/cmserr.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
