# `blst` `0.3.16`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/blst-c4021da583f59d00/out/libblst.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-1q6jbbrz/src/blst-0.3.16`

### Source directories

* `/tmp/crate-build-ppc64le-1q6jbbrz/src/blst-0.3.16/blst/src`

### Source file examples

* `/tmp/crate-build-ppc64le-1q6jbbrz/src/blst-0.3.16/blst/src/server.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-1q6jbbrz/src/blst-0.3.16`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -fno-builtin -Wno-unused-function -Wno-unused-command-line-argument -D__BLST_NO_ASM__ -o /target/powerpc64le-unknown-linux-gnu/debug/build/blst-c4021da583f59d00/out/3ce72ea41a6346fd-server.o -c /tmp/crate-build-ppc64le-1q6jbbrz/src/blst-0.3.16/blst/src/server.c
```

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu -D __BLST_NO_ASM__ <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-function ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
