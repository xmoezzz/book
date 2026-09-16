# `ducc-sys` `0.1.2`

Platform: Linux x86_64

## `/work/target/debug/build/ducc-sys-b13a512e38a658e1/out/libduktape.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/duktape`

### Source file examples

* `/work/duktape/duktape.c`
* `/work/duktape/wrapper.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I duktape -Wall -Wextra -std=c99 -o /work/target/debug/build/ducc-sys-b13a512e38a658e1/out/duktape/duktape.o -c duktape/duktape.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I duktape -imultiarch x86_64-linux-gnu duktape/duktape.c -quiet -dumpdir /work/target/debug/build/ducc-sys-b13a512e38a658e1/out/duktape/ -dumpbase duktape.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -O0 -Wall ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I duktape -Wall -Wextra -std=c99 -o /work/target/debug/build/ducc-sys-b13a512e38a658e1/out/duktape/wrapper.o -c duktape/wrapper.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I duktape -imultiarch x86_64-linux-gnu duktape/wrapper.c -quiet -dumpdir /work/target/debug/build/ducc-sys-b13a512e38a658e1/out/duktape/ -dumpbase wrapper.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -O0 -Wall ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I <include directory> -Wall -Wextra -std=c99 -o <object> -c <source>
```

### Static library construction

```text
ar crs <static library> <object files>
```
