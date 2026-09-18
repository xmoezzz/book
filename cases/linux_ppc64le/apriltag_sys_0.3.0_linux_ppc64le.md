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

### Compilation

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -o <object> -c <source>
```

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -ffunction-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
