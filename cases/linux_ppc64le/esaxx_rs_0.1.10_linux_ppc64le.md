# `esaxx-rs` `0.1.10`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10`

### Source directories

* `/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10/src`

### Source file examples

* `/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10/src/esaxx.cpp`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10`

```text
/usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src -Wall -Wextra -std=c++11 -o /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o -c src/esaxx.cpp
```

### Compilation

```text
cc1plus -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
