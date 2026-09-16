# `link-cplusplus` `1.0.9`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/link-cplusplus-9d9b18caa612ab80/out/liblink-cplusplus.a`

### Source origin

* matches Linux x86_64 source path `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out/dummy.cc`, under build output directory `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out`

### Source directories

* `/target/powerpc64le-unknown-linux-gnu/debug/build/link-cplusplus-9d9b18caa612ab80/out`

### Source file examples

* `/target/powerpc64le-unknown-linux-gnu/debug/build/link-cplusplus-9d9b18caa612ab80/out/dummy.cc`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-vg5df9co/src/link-cplusplus-1.0.9`

```text
/usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/link-cplusplus-9d9b18caa612ab80/out/a224c9c081e7ef67-dummy.o -c /target/powerpc64le-unknown-linux-gnu/debug/build/link-cplusplus-9d9b18caa612ab80/out/dummy.cc
```

### Compilation

```text
cc1plus -quiet -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
