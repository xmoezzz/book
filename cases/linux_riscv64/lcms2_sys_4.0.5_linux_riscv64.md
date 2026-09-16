# `lcms2-sys` `4.0.5`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/lcms2-sys-8eee6c11efa1d417/out/liblcms2.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5`

### Source directories

* `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5/vendor/src`

### Source file examples

* `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5/vendor/src/cmsalpha.c`
* `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5/vendor/src/cmscam02.c`
* `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5/vendor/src/cmscgats.c`
* `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5/vendor/src/cmscnvrt.c`
* `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5/vendor/src/cmserr.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I vendor/include -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/lcms2-sys-8eee6c11efa1d417/out/49c72391db7e6a2b-cmsalpha.o -c vendor/src/cmsalpha.c
```

Working directory: `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I vendor/include -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/lcms2-sys-8eee6c11efa1d417/out/49c72391db7e6a2b-cmscam02.o -c vendor/src/cmscam02.c
```

Working directory: `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I vendor/include -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/lcms2-sys-8eee6c11efa1d417/out/49c72391db7e6a2b-cmscgats.o -c vendor/src/cmscgats.c
```

Working directory: `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I vendor/include -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/lcms2-sys-8eee6c11efa1d417/out/49c72391db7e6a2b-cmscnvrt.o -c vendor/src/cmscnvrt.c
```

Working directory: `/tmp/crate-build-riscv64-9922qr03/src/lcms2-sys-4.0.5`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I vendor/include -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/lcms2-sys-8eee6c11efa1d417/out/49c72391db7e6a2b-cmserr.o -c vendor/src/cmserr.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/lcms2-sys-8eee6c11efa1d417/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
