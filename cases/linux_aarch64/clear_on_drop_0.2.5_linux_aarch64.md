# `clear_on_drop` `0.2.5`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5`

### Source directories

* `/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5/src`

### Source file examples

* `/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5/src/hide.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o -c src/hide.c
```

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
