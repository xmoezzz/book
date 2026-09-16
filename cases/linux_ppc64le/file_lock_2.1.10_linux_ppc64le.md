# `file-lock` `2.1.10`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/libfile_lock.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-e_efncmo/src/file-lock-2.1.10`

### Source directories

* `/tmp/crate-build-ppc64le-e_efncmo/src/file-lock-2.1.10/src`

### Source file examples

* `/tmp/crate-build-ppc64le-e_efncmo/src/file-lock-2.1.10/src/file_lock.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-e_efncmo/src/file-lock-2.1.10`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/ea708c7824d36062-file_lock.o -c src/file_lock.c
```

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
