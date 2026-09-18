# `lz4-sys` `1.11.1+lz4-1.10.0`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/lz4-sys-18684ad79a9c35ae/out/liblz4.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-2p3k0cqb/src/lz4-sys-1.11.1+lz4-1.10.0`

### Source directories

* `/tmp/crate-build-ppc64le-2p3k0cqb/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib`

### Source file examples

* `/tmp/crate-build-ppc64le-2p3k0cqb/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4.c`
* `/tmp/crate-build-ppc64le-2p3k0cqb/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4frame.c`
* `/tmp/crate-build-ppc64le-2p3k0cqb/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4hc.c`
* `/tmp/crate-build-ppc64le-2p3k0cqb/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/xxhash.c`

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O3 -Wall -Wextra -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
