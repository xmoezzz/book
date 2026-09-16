# `ittapi-sys` `0.4.0`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/libittnotify.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0`

### Source directories

* `/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0/c-library/src/ittnotify`

### Source file examples

* `/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0/c-library/src/ittnotify/ittnotify_static.c`
* `/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0/c-library/src/ittnotify/jitprofiling.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I c-library/src/ittnotify/ -I c-library/include/ -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o -c c-library/src/ittnotify/ittnotify_static.c
```

Working directory: `/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I c-library/src/ittnotify/ -I c-library/include/ -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o -c c-library/src/ittnotify/jitprofiling.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
