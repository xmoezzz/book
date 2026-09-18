# `link-cplusplus` `1.0.9`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/link-cplusplus-cdb1f6d660ef701c/out/liblink-cplusplus.a`

### Source origin

* matches Linux x86_64 source path `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out/dummy.cc`, under build output directory `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out`

### Source directories

* `/target/riscv64gc-unknown-linux-gnu/debug/build/link-cplusplus-cdb1f6d660ef701c/out`

### Source file examples

* `/target/riscv64gc-unknown-linux-gnu/debug/build/link-cplusplus-cdb1f6d660ef701c/out/dummy.cc`

### Compilation

```text
cc1plus -quiet -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/link-cplusplus-cdb1f6d660ef701c/out/ -dumpbase <source> -dumpbase-ext .cc -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
