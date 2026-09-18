# `ittapi-sys` `0.4.0`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/libittnotify.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0`

### Source directories

* `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0/c-library/src/ittnotify`

### Source file examples

* `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0/c-library/src/ittnotify/ittnotify_static.c`
* `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0/c-library/src/ittnotify/jitprofiling.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
