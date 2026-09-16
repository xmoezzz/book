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

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I apriltag-src -Wall -o /work/target/debug/build/apriltag-sys-994878befa074a2f/out/f0c75187ad69178f-tagStandard41h12.o -c apriltag-src/tagStandard41h12.c
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I apriltag-src -Wall -o /work/target/debug/build/apriltag-sys-994878befa074a2f/out/f0c75187ad69178f-tagStandard52h13.o -c apriltag-src/tagStandard52h13.c
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I apriltag-src -Wall -o /work/target/debug/build/apriltag-sys-994878befa074a2f/out/f0c75187ad69178f-tagCircle49h12.o -c apriltag-src/tagCircle49h12.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I apriltag-src -imultiarch x86_64-linux-gnu apriltag-src/tagStandard52h13.c -quiet -dumpdir /work/target/debug/build/apriltag-sys-994878befa074a2f/out/ -dumpbase f0c75187ad69178f-tagStandard52h13.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I apriltag-src -Wall -o /work/target/debug/build/apriltag-sys-994878befa074a2f/out/f0c75187ad69178f-tagCustom48h12.o -c apriltag-src/tagCustom48h12.c
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
