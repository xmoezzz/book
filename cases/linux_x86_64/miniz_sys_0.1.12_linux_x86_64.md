# `miniz-sys` `0.1.12`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 2131259

Build-script executable: `/work/target/debug/build/miniz-sys-1ed37f2643f8bb90/build_script_build-1ed37f2643f8bb90`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/miniz-sys-21d1cb3132dd7174/out/libminiz.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work`

### Source file examples

* `/work/miniz.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -w -fvisibility=hidden -DMINIZ_NO_STDIO -DMINIZ_NO_ARCHIVE_APIS -DMINIZ_NO_ARCHIVE_WRITING_APIS -DMINIZ_NO_TIME -DMINIZ_NO_ZLIB_COMPATIBLE_NAMES -o /work/target/debug/build/miniz-sys-21d1cb3132dd7174/out/db3b6bfb95261072-miniz.o -c miniz.c ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu -D MINIZ_NO_STDIO -D MINIZ_NO_ARCHIVE_APIS -D MINIZ_NO_ARCHIVE_WRITING_APIS -D MINIZ_NO_TIME -D MINIZ_NO_ZLIB_COMPATIBLE_NAMES miniz.c -quiet -dumpdir /work/target/debug/build/miniz-sys-21d1cb3132dd7174/out/ -dumpbase db3b6bfb95261072-miniz.c ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -w -fvisibility=hidden -DMINIZ_NO_STDIO -DMINIZ_NO_ARCHIVE_APIS -DMINIZ_NO_ARCHIVE_WRITING_APIS -DMINIZ_NO_TIME -DMINIZ_NO_ZLIB_COMPATIBLE_NAMES -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
