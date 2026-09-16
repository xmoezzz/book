# `alloca` `0.4.0`

Platform: Linux x86_64

## `/work/target/debug/build/alloca-0c6e0ff4e7a0aa76/out/libcalloca.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work`

### Source file examples

* `/work/alloca.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /work/target/debug/build/alloca-0c6e0ff4e7a0aa76/out/alloca.o -c alloca.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu alloca.c -quiet -dumpdir /work/target/debug/build/alloca-0c6e0ff4e7a0aa76/out/ -dumpbase alloca.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -gdwarf-4 -O2 -Wall -Wextra -ffunction-sections ...
```

### Compilation

```text
cc -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
