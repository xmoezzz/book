# `dart-sys` `4.1.5`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/dart-sys-c5f79a256687a864/out/libdart_api_dl.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5`

### Source directories

* `/tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5/dart-sdk/include`

### Source file examples

* `/tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5/dart-sdk/include/dart_api_dl.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5/dart-sdk/include -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/dart-sys-c5f79a256687a864/out/248f927bf32daba4-dart_api_dl.o -c /tmp/crate-build-aarch64-y29nacli/src/dart-sys-4.1.5/dart-sdk/include/dart_api_dl.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
