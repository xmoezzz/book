# `apriltag-sys` `0.3.0`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 807171

Build-script executable: `/target/debug/build/apriltag-sys-453c13b4e4c34714/build_script_build-453c13b4e4c34714`

Working directory: `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0`

Full linker command: retained in the raw case.

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/apriltag-sys-dd8321a6aa711997/out/libapriltags.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0`

### Source directories

* `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0/apriltag-src`
* `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0/apriltag-src/common`

### Source file examples

* `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0/apriltag-src/apriltag.c`
* `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0/apriltag-src/apriltag_pose.c`
* `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0/apriltag-src/apriltag_quad_thresh.c`
* `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0/apriltag-src/common/unionfind.c`
* `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0/apriltag-src/common/workerpool.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0`

```text
/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I apriltag-src -imultiarch powerpc64le-linux-gnu apriltag-src/tagStandard52h13.c -msecure-plt -quiet -dumpbase tagStandard52h13.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/apriltag-sys-dd8321a6aa711997/out/f0c75187ad69178f-tagStandard52h13.o -g -gdwarf-4 -O0 -Wall -ffunction-sections ...
```

Working directory: `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0`

```text
/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I apriltag-src -imultiarch powerpc64le-linux-gnu apriltag-src/tagStandard41h12.c -msecure-plt -quiet -dumpbase tagStandard41h12.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/apriltag-sys-dd8321a6aa711997/out/f0c75187ad69178f-tagStandard41h12.o -g -gdwarf-4 -O0 -Wall -ffunction-sections ...
```

Working directory: `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I apriltag-src -Wall -o /target/powerpc64le-unknown-linux-gnu/debug/build/apriltag-sys-dd8321a6aa711997/out/f0c75187ad69178f-tagCustom48h12.o -c apriltag-src/tagCustom48h12.c
```

Working directory: `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I apriltag-src -Wall -o /target/powerpc64le-unknown-linux-gnu/debug/build/apriltag-sys-dd8321a6aa711997/out/f0c75187ad69178f-tagCircle49h12.o -c apriltag-src/tagCircle49h12.c
```

Working directory: `/tmp/crate-build-ppc64le-snmerfsd/src/apriltag-sys-0.3.0`

```text
/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I apriltag-src -imultiarch powerpc64le-linux-gnu apriltag-src/tagCircle21h7.c -msecure-plt -quiet -dumpbase tagCircle21h7.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/apriltag-sys-dd8321a6aa711997/out/f0c75187ad69178f-tagCircle21h7.o -g -gdwarf-4 -O0 -Wall -ffunction-sections ...
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -ffunction-sections ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
