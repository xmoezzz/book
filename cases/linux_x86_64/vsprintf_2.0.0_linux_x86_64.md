# `vsprintf` `2.0.0`

Platform: Linux x86_64

## `/work/target/debug/build/vsprintf-86b84f12925e1eb7/out/libvsprintf.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/lib.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /work/target/debug/build/vsprintf-86b84f12925e1eb7/out/ea708c7824d36062-lib.o -c src/lib.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu src/lib.c -quiet -dumpdir /work/target/debug/build/vsprintf-86b84f12925e1eb7/out/ -dumpbase ea708c7824d36062-lib.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
