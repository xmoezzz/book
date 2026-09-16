# `sys-info` `0.9.1`

Platform: Linux x86_64

## `/work/target/debug/build/sys-info-ef69c1aa66bca0e5/out/libinfo.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/c`

### Source file examples

* `/work/c/linux.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /work/target/debug/build/sys-info-ef69c1aa66bca0e5/out/a1edd97dd51cd48d-linux.o -c c/linux.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu c/linux.c -quiet -dumpdir /work/target/debug/build/sys-info-ef69c1aa66bca0e5/out/ -dumpbase a1edd97dd51cd48d-linux.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
