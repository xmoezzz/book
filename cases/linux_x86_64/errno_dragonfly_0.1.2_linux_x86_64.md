# `errno-dragonfly` `0.1.2`

Platform: Linux x86_64

## `/work/target/debug/build/errno-dragonfly-f6881ba4cb8d301e/out/liberrno.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/errno.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /work/target/debug/build/errno-dragonfly-f6881ba4cb8d301e/out/ea708c7824d36062-errno.o -c src/errno.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu src/errno.c -quiet -dumpdir /work/target/debug/build/errno-dragonfly-f6881ba4cb8d301e/out/ -dumpbase ea708c7824d36062-errno.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
