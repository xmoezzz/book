# `tracy-client-sys` `0.21.0`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/tracy-client-sys-a719c4af516b378d/out/libtracy-client.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-ai9j_81h/src/tracy-client-sys-0.21.0`

### Source directories

* `/tmp/crate-build-aarch64-ai9j_81h/src/tracy-client-sys-0.21.0/tracy`

### Source file examples

* `/tmp/crate-build-aarch64-ai9j_81h/src/tracy-client-sys-0.21.0/tracy/TracyClient.cpp`

### Compilation

```text
cc1plus -quiet -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D TRACY_ENABLE <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -w -std=c++11 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
