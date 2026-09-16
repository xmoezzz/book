# `rav1e` `0.7.1`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/rav1e-42dd61522fe100f1/out/librav1e-aarch64.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1`

### Source directories

* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm`
* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64`

### Source file examples

* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64/cdef.S`
* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64/cdef16.S`
* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64/cdef_dist.S`
* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64/ipred.S`
* `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1/src/arm/64/ipred16.S`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O1 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I . -I /target/aarch64-unknown-linux-gnu/debug/build/rav1e-42dd61522fe100f1/out -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/rav1e-42dd61522fe100f1/out/src/arm/64/cdef16.o -c src/arm/64/cdef16.S
```

Working directory: `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1`

```text
/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I . -I /target/aarch64-unknown-linux-gnu/debug/build/rav1e-42dd61522fe100f1/out -imultiarch aarch64-linux-gnu src/arm/64/cdef.S -mlittle-endian -mabi=lp64 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -gdwarf-4 ...
```

Working directory: `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O1 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I . -I /target/aarch64-unknown-linux-gnu/debug/build/rav1e-42dd61522fe100f1/out -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/rav1e-42dd61522fe100f1/out/src/arm/64/cdef_dist.o -c src/arm/64/cdef_dist.S
```

Working directory: `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O1 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I . -I /target/aarch64-unknown-linux-gnu/debug/build/rav1e-42dd61522fe100f1/out -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/rav1e-42dd61522fe100f1/out/src/arm/64/mc.o -c src/arm/64/mc.S
```

Working directory: `/tmp/crate-build-aarch64-qtua4pf4/src/rav1e-0.7.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O1 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I . -I /target/aarch64-unknown-linux-gnu/debug/build/rav1e-42dd61522fe100f1/out -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/rav1e-42dd61522fe100f1/out/src/arm/64/mc16.o -c src/arm/64/mc16.S
```

### Compilation

```text
cc1 -E -lang-asm -quiet -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu <source> -mlittle-endian -mabi=lp64 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -gdwarf-4 ...
```

```text
gcc -O1 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I <include directory> -I <include directory> -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
