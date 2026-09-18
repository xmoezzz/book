# `cxx` `1.0.128`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/cxx-2d3bb8e380ecdc12/out/libcxxbridge1.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-urhjgobl/src/cxx-1.0.128`

### Source directories

* `/tmp/crate-build-riscv64-urhjgobl/src/cxx-1.0.128/src`

### Source file examples

* `/tmp/crate-build-riscv64-urhjgobl/src/cxx-1.0.128/src/cxx.cc`

### Compilation

```text
cc1plus -quiet -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/cxx-2d3bb8e380ecdc12/out/ -dumpbase <source> -dumpbase-ext .cc -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
