# `apriltag-sys` `0.3.0`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/apriltag-sys-54cbf29b0241571f/out/libapriltags.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0`

### Source directories

* `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0/apriltag-src`
* `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0/apriltag-src/common`

### Source file examples

* `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0/apriltag-src/apriltag.c`
* `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0/apriltag-src/apriltag_pose.c`
* `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0/apriltag-src/apriltag_quad_thresh.c`
* `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0/apriltag-src/common/unionfind.c`
* `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0/apriltag-src/common/workerpool.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/apriltag-sys-54cbf29b0241571f/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I <include directory> -Wall -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
