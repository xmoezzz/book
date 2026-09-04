# `tracy-client-sys` `0.21.0`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/tracy-client-sys-59c5d520ece1f23a/out/libtracy-client.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-zi3qw7dl/src/tracy-client-sys-0.21.0`

### Source directories

* `/tmp/crate-build-ppc64le-zi3qw7dl/src/tracy-client-sys-0.21.0/tracy`

### Source file examples

* `/tmp/crate-build-ppc64le-zi3qw7dl/src/tracy-client-sys-0.21.0/tracy/TracyClient.cpp`

### Compilation

```text
cc1plus -quiet -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D TRACY_ENABLE <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -w ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
