# `iana-time-zone-haiku` `0.1.2`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/iana-time-zone-haiku-bfab047517a46b99/out/libtz_haiku.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-sb1e4l9t/src/iana-time-zone-haiku-0.1.2`

### Source directories

* `/tmp/crate-build-riscv64-sb1e4l9t/src/iana-time-zone-haiku-0.1.2/src`

### Source file examples

* `/tmp/crate-build-riscv64-sb1e4l9t/src/iana-time-zone-haiku-0.1.2/src/implementation.cc`

### Compilation

```text
cc1plus -quiet -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/iana-time-zone-haiku-bfab047517a46b99/out/ -dumpbase <source> -dumpbase-ext .cc -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
