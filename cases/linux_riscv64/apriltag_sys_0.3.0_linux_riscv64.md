# `apriltag-sys` `0.3.0`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 807813

Build-script executable: `/target/debug/build/apriltag-sys-453c13b4e4c34714/build_script_build-453c13b4e4c34714`

Working directory: `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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

### Source preparation

Working directory: `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I apriltag-src -Wall -o /target/riscv64gc-unknown-linux-gnu/debug/build/apriltag-sys-54cbf29b0241571f/out/f0c75187ad69178f-tagStandard52h13.o -c apriltag-src/tagStandard52h13.c
```

Working directory: `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I apriltag-src -Wall -o /target/riscv64gc-unknown-linux-gnu/debug/build/apriltag-sys-54cbf29b0241571f/out/f0c75187ad69178f-tagStandard41h12.o -c apriltag-src/tagStandard41h12.c
```

Working directory: `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0`

```text
/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I apriltag-src -imultilib . -imultiarch riscv64-linux-gnu apriltag-src/tagCustom48h12.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/apriltag-sys-54cbf29b0241571f/out/ -dumpbase f0c75187ad69178f-tagCustom48h12.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

Working directory: `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I apriltag-src -Wall -o /target/riscv64gc-unknown-linux-gnu/debug/build/apriltag-sys-54cbf29b0241571f/out/f0c75187ad69178f-tagCircle49h12.o -c apriltag-src/tagCircle49h12.c
```

Working directory: `/tmp/crate-build-riscv64-ue2uap0r/src/apriltag-sys-0.3.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I apriltag-src -Wall -o /target/riscv64gc-unknown-linux-gnu/debug/build/apriltag-sys-54cbf29b0241571f/out/f0c75187ad69178f-tagCircle21h7.o -c apriltag-src/tagCircle21h7.c
```

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
