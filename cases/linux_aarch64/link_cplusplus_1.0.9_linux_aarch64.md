# `link-cplusplus` `1.0.9`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/link-cplusplus-a5d8ff51e518fad5/out/liblink-cplusplus.a`

### Source origin

* matches Linux x86_64 source path `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out/dummy.cc`, under build output directory `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out`

### Source directories

* `/target/aarch64-unknown-linux-gnu/debug/build/link-cplusplus-a5d8ff51e518fad5/out`

### Source file examples

* `/target/aarch64-unknown-linux-gnu/debug/build/link-cplusplus-a5d8ff51e518fad5/out/dummy.cc`

### Compilation

```text
cc1plus -quiet -imultiarch aarch64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
