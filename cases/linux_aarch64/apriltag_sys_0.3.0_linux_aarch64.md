# `apriltag-sys` `0.3.0`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 807685

Build-script executable: `/target/debug/build/apriltag-sys-453c13b4e4c34714/build_script_build-453c13b4e4c34714`

Working directory: `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/aarch64-unknown-linux-gnu/debug/build/apriltag-sys-b0d9b762630146c2/out/libapriltags.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0`

### Source directories

* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src`
* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/common`

### Source file examples

* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/apriltag.c`
* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/apriltag_pose.c`
* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/apriltag_quad_thresh.c`
* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/common/unionfind.c`
* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/common/workerpool.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I apriltag-src -Wall -o /target/aarch64-unknown-linux-gnu/debug/build/apriltag-sys-b0d9b762630146c2/out/f0c75187ad69178f-tagStandard52h13.o -c apriltag-src/tagStandard52h13.c
```

Working directory: `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I apriltag-src -Wall -o /target/aarch64-unknown-linux-gnu/debug/build/apriltag-sys-b0d9b762630146c2/out/f0c75187ad69178f-tagCustom48h12.o -c apriltag-src/tagCustom48h12.c
```

Working directory: `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0`

```text
/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I apriltag-src -imultiarch aarch64-linux-gnu apriltag-src/tagStandard41h12.c -quiet -dumpbase tagStandard41h12.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/apriltag-sys-b0d9b762630146c2/out/f0c75187ad69178f-tagStandard41h12.o -g -gdwarf-4 -O0 -Wall -ffunction-sections -fdata-sections ...
```

Working directory: `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I apriltag-src -Wall -o /target/aarch64-unknown-linux-gnu/debug/build/apriltag-sys-b0d9b762630146c2/out/f0c75187ad69178f-tagCircle49h12.o -c apriltag-src/tagCircle49h12.c
```

Working directory: `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I apriltag-src -Wall -o /target/aarch64-unknown-linux-gnu/debug/build/apriltag-sys-b0d9b762630146c2/out/f0c75187ad69178f-tagCircle21h7.o -c apriltag-src/tagCircle21h7.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -ffunction-sections -fdata-sections ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I <include directory> -Wall -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
