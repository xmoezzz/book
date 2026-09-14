# `lz4-sys` `1.11.1+lz4-1.10.0`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1836491

Build-script executable: `/work/target/debug/build/lz4-sys-7886d9e8cb21264f/build_script_build-7886d9e8cb21264f`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/lz4-sys-544d4bf21ea43c0f/out/liblz4.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/liblz4/lib`

### Source file examples

* `/work/liblz4/lib/lz4.c`
* `/work/liblz4/lib/lz4frame.c`
* `/work/liblz4/lib/lz4hc.c`
* `/work/liblz4/lib/xxhash.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /work/target/debug/build/lz4-sys-544d4bf21ea43c0f/out/efce31824dbf3730-lz4.o -c liblz4/lib/lz4.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu liblz4/lib/lz4.c -quiet -dumpdir /work/target/debug/build/lz4-sys-544d4bf21ea43c0f/out/ -dumpbase efce31824dbf3730-lz4.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O3 -Wall -Wextra ...
```

Working directory: `/work`

```text
/usr/bin/cc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /work/target/debug/build/lz4-sys-544d4bf21ea43c0f/out/efce31824dbf3730-lz4frame.o -c liblz4/lib/lz4frame.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu liblz4/lib/lz4frame.c -quiet -dumpdir /work/target/debug/build/lz4-sys-544d4bf21ea43c0f/out/ -dumpbase efce31824dbf3730-lz4frame.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O3 -Wall -Wextra ...
```

Working directory: `/work`

```text
/usr/bin/cc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /work/target/debug/build/lz4-sys-544d4bf21ea43c0f/out/efce31824dbf3730-lz4hc.o -c liblz4/lib/lz4hc.c
```

### Compilation

```text
cc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
