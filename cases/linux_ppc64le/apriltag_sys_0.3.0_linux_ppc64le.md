# `apriltag-sys` `0.3.0`

Platform: Linux ppc64le

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
