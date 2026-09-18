# `apriltag-sys` `0.3.0`

Platform: Linux x86_64

## `/work/target/debug/build/apriltag-sys-994878befa074a2f/out/libapriltags.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/apriltag-src`
* `/work/apriltag-src/common`

### Source file examples

* `/work/apriltag-src/apriltag.c`
* `/work/apriltag-src/apriltag_pose.c`
* `/work/apriltag-src/apriltag_quad_thresh.c`
* `/work/apriltag-src/common/g2d.c`
* `/work/apriltag-src/common/getopt.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
