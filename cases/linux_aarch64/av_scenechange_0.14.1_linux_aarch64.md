# `av-scenechange` `0.14.1`

Platform: Linux aarch64

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

### Compilation

```text
cc1 -E -lang-asm -quiet -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu <source> -mlittle-endian -mabi=lp64 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -gdwarf-4 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
