# `av-scenechange` `0.14.1`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 537360

Build-script executable: `/target/debug/build/av-scenechange-d4dc305b1a920ba5/build_script_build-d4dc305b1a920ba5`

Working directory: `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/av-scenechange-0236b9f8ccc13322/out/libavsc-aarch64.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1`

### Source directories

* `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1/src/asm/arm`
* `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1/src/asm/arm/64`

### Source file examples

* `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1/src/asm/arm/64/ipred.S`
* `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1/src/asm/arm/64/ipred16.S`
* `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1/src/asm/arm/64/mc.S`
* `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1/src/asm/arm/64/mc16.S`
* `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1/src/asm/arm/64/satd.S`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I . -I /target/aarch64-unknown-linux-gnu/debug/build/av-scenechange-0236b9f8ccc13322/out -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/av-scenechange-0236b9f8ccc13322/out/d3c8c71c163dd1a4-mc.o -c src/asm/arm/64/mc.S
```

Working directory: `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I . -I /target/aarch64-unknown-linux-gnu/debug/build/av-scenechange-0236b9f8ccc13322/out -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/av-scenechange-0236b9f8ccc13322/out/d3c8c71c163dd1a4-mc16.o -c src/asm/arm/64/mc16.S
```

Working directory: `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I . -I /target/aarch64-unknown-linux-gnu/debug/build/av-scenechange-0236b9f8ccc13322/out -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/av-scenechange-0236b9f8ccc13322/out/d3c8c71c163dd1a4-ipred.o -c src/asm/arm/64/ipred.S
```

Working directory: `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I . -I /target/aarch64-unknown-linux-gnu/debug/build/av-scenechange-0236b9f8ccc13322/out -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/av-scenechange-0236b9f8ccc13322/out/d3c8c71c163dd1a4-ipred16.o -c src/asm/arm/64/ipred16.S
```

Working directory: `/tmp/crate-build-aarch64-n6vby1d1/src/av-scenechange-0.14.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I . -I /target/aarch64-unknown-linux-gnu/debug/build/av-scenechange-0236b9f8ccc13322/out -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/av-scenechange-0236b9f8ccc13322/out/d3c8c71c163dd1a4-satd.o -c src/asm/arm/64/satd.S
```

### Compilation

```text
cc1 -E -lang-asm -quiet -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu <source> -mlittle-endian -mabi=lp64 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -gdwarf-4 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
