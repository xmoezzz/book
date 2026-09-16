# `vsprintf` `2.0.0`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/libvsprintf.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0`

### Source directories

* `/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0/src`

### Source file examples

* `/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0/src/lib.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o -c src/lib.c
```

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
