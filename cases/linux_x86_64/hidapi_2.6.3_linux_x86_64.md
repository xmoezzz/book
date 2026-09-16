# `hidapi` `2.6.3`

Platform: Linux x86_64

## Build-level coding evidence

### pkg-config / pkgconf

Working directory: `/work`

```text
pkg-config --libs --cflags libudev
```

Working directory: `/work`

```text
pkg-config --modversion libudev
```

## `/work/target/debug/build/hidapi-804845236c584c2b/out/libhidapi.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/etc/hidapi/linux`

### Source file examples

* `/work/etc/hidapi/linux/hid.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I etc/hidapi/hidapi -Wall -Wextra -o /work/target/debug/build/hidapi-804845236c584c2b/out/etc/hidapi/linux/hid.o -c etc/hidapi/linux/hid.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I etc/hidapi/hidapi -imultiarch x86_64-linux-gnu etc/hidapi/linux/hid.c -quiet -dumpdir /work/target/debug/build/hidapi-804845236c584c2b/out/etc/hidapi/linux/ -dumpbase hid.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -gdwarf-4 -O0 -Wall ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
