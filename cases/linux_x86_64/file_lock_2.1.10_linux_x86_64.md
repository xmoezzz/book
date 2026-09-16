# `file-lock` `2.1.10`

Platform: Linux x86_64

## `/work/target/debug/build/file-lock-bfe8616c7d66d83d/out/libfile_lock.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/file_lock.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /work/target/debug/build/file-lock-bfe8616c7d66d83d/out/ea708c7824d36062-file_lock.o -c src/file_lock.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu src/file_lock.c -quiet -dumpdir /work/target/debug/build/file-lock-bfe8616c7d66d83d/out/ -dumpbase ea708c7824d36062-file_lock.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
