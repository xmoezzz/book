# `ittapi-sys` `0.4.0`

Platform: Linux x86_64

## `/work/target/debug/build/ittapi-sys-f438b9b74b041e0a/out/libittnotify.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/c-library/src/ittnotify`

### Source file examples

* `/work/c-library/src/ittnotify/ittnotify_static.c`
* `/work/c-library/src/ittnotify/jitprofiling.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I c-library/src/ittnotify/ -I c-library/include/ -Wall -Wextra -o /work/target/debug/build/ittapi-sys-f438b9b74b041e0a/out/48f6f8d8d7ef524e-ittnotify_static.o -c c-library/src/ittnotify/ittnotify_static.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I c-library/src/ittnotify/ -I c-library/include/ -imultiarch x86_64-linux-gnu c-library/src/ittnotify/ittnotify_static.c -quiet -dumpdir /work/target/debug/build/ittapi-sys-f438b9b74b041e0a/out/ -dumpbase 48f6f8d8d7ef524e-ittnotify_static.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I c-library/src/ittnotify/ -I c-library/include/ -Wall -Wextra -o /work/target/debug/build/ittapi-sys-f438b9b74b041e0a/out/48f6f8d8d7ef524e-jitprofiling.o -c c-library/src/ittnotify/jitprofiling.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I c-library/src/ittnotify/ -I c-library/include/ -imultiarch x86_64-linux-gnu c-library/src/ittnotify/jitprofiling.c -quiet -dumpdir /work/target/debug/build/ittapi-sys-f438b9b74b041e0a/out/ -dumpbase 48f6f8d8d7ef524e-jitprofiling.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
