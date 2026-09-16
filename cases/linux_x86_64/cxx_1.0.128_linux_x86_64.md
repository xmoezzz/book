# `cxx` `1.0.128`

Platform: Linux x86_64

## `/work/target/debug/build/cxx-c5ee6af0ce76b4cd/out/libcxxbridge1.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/cxx.cc`

### Source preparation

Working directory: `/work`

```text
/usr/bin/c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++11 -Wall -Wextra -o /work/target/debug/build/cxx-c5ee6af0ce76b4cd/out/c16f17691ff6f04b-cxx.o -c /work/src/cxx.cc
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1plus -quiet -imultiarch x86_64-linux-gnu -D_GNU_SOURCE /work/src/cxx.cc -quiet -dumpdir /work/target/debug/build/cxx-c5ee6af0ce76b4cd/out/ -dumpbase c16f17691ff6f04b-cxx.cc -dumpbase-ext .cc -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 -Wall ...
```

### Compilation

```text
c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++11 -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
