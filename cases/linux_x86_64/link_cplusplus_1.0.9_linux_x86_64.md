# `link-cplusplus` `1.0.9`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 1857794

Build-script executable: `/work/target/debug/build/link-cplusplus-b5476580f5a25879/build_script_build-b5476580f5a25879`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out/liblink-cplusplus.a`

### Source origin

* under build output directory `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out`

### Source directories

* `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out`

### Source file examples

* `/work/target/debug/build/link-cplusplus-694b35d726c37ea0/out/dummy.cc`

### Source preparation

Working directory: `/work`

```text
/usr/bin/c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /work/target/debug/build/link-cplusplus-694b35d726c37ea0/out/4528f283a14a17fe-dummy.o -c /work/target/debug/build/link-cplusplus-694b35d726c37ea0/out/dummy.cc
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1plus -quiet -imultiarch x86_64-linux-gnu -D_GNU_SOURCE /work/target/debug/build/link-cplusplus-694b35d726c37ea0/out/dummy.cc -quiet -dumpdir /work/target/debug/build/link-cplusplus-694b35d726c37ea0/out/ -dumpbase 4528f283a14a17fe-dummy.cc -dumpbase-ext .cc -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 -Wall ...
```

### Compilation

```text
c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
