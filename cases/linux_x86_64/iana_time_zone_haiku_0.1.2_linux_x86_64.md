# `iana-time-zone-haiku` `0.1.2`

Platform: Linux x86_64

## `/work/target/debug/build/iana-time-zone-haiku-06660e3e84a08f7e/out/libtz_haiku.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/implementation.cc`

### Source preparation

Working directory: `/work`

```text
/usr/bin/c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -w -o /work/target/debug/build/iana-time-zone-haiku-06660e3e84a08f7e/out/48d3f1b29a630f4c-implementation.o -c src/implementation.cc
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1plus -quiet -imultiarch x86_64-linux-gnu -D_GNU_SOURCE src/implementation.cc -quiet -dumpdir /work/target/debug/build/iana-time-zone-haiku-06660e3e84a08f7e/out/ -dumpbase 48d3f1b29a630f4c-implementation.cc -dumpbase-ext .cc -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 -w ...
```

### Compilation

```text
c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -w -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
