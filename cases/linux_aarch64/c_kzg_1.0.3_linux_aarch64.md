# `c-kzg` `1.0.3`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/c-kzg-1599ee71ecaeb2bb/out/libckzg.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3`

### Source directories

* `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3/src`

### Source file examples

* `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3/src/c_kzg_4844.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3/blst/bindings -w -o /target/aarch64-unknown-linux-gnu/debug/build/c-kzg-1599ee71ecaeb2bb/out/98490c8781b409d2-c_kzg_4844.o -c /tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3/src/c_kzg_4844.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -w -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
