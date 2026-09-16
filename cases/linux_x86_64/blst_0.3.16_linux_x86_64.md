# `blst` `0.3.16`

Platform: Linux x86_64

## `/work/target/debug/build/blst-1a71e90ce1f068b5/out/libblst.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/blst/build`
* `/work/blst/src`

### Source file examples

* `/work/blst/build/assembly.S`
* `/work/blst/src/server.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -D__ADX__ -o /work/target/debug/build/blst-1a71e90ce1f068b5/out/3ce72ea41a6346fd-server.o -c /work/blst/src/server.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu -D __ADX__ /work/blst/src/server.c -quiet -dumpdir /work/target/debug/build/blst-1a71e90ce1f068b5/out/ -dumpbase 3ce72ea41a6346fd-server.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -gdwarf-4 -O0 -Wall ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -D__ADX__ -o /work/target/debug/build/blst-1a71e90ce1f068b5/out/f6e817b043e0335b-assembly.o -c /work/blst/build/assembly.S
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -E -lang-asm -quiet -imultiarch x86_64-linux-gnu -D __ADX__ /work/blst/build/assembly.S -m64 -mtune=generic -march=x86-64 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -gdwarf-4 -fworking-directory ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -D__ADX__ -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
