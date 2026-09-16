# `c-kzg` `1.0.3`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/c-kzg-408a003be16433a9/out/libckzg.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-8aox0qfj/src/c-kzg-1.0.3`

### Source directories

* `/tmp/crate-build-ppc64le-8aox0qfj/src/c-kzg-1.0.3/src`

### Source file examples

* `/tmp/crate-build-ppc64le-8aox0qfj/src/c-kzg-1.0.3/src/c_kzg_4844.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-8aox0qfj/src/c-kzg-1.0.3`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-8aox0qfj/src/c-kzg-1.0.3/blst/bindings -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/c-kzg-408a003be16433a9/out/98490c8781b409d2-c_kzg_4844.o -c /tmp/crate-build-ppc64le-8aox0qfj/src/c-kzg-1.0.3/src/c_kzg_4844.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -w -ffunction-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
