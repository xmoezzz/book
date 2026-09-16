# `lcms2-sys` `4.0.5`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/lcms2-sys-291f8ed5f45995e7/out/liblcms2.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5`

### Source directories

* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src`

### Source file examples

* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src/cmsalpha.c`
* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src/cmscam02.c`
* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src/cmscgats.c`
* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src/cmscnvrt.c`
* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src/cmserr.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I vendor/include -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/lcms2-sys-291f8ed5f45995e7/out/49c72391db7e6a2b-cmsalpha.o -c vendor/src/cmsalpha.c
```

Working directory: `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I vendor/include -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/lcms2-sys-291f8ed5f45995e7/out/49c72391db7e6a2b-cmscam02.o -c vendor/src/cmscam02.c
```

Working directory: `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I vendor/include -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/lcms2-sys-291f8ed5f45995e7/out/49c72391db7e6a2b-cmscgats.o -c vendor/src/cmscgats.c
```

Working directory: `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I vendor/include -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/lcms2-sys-291f8ed5f45995e7/out/49c72391db7e6a2b-cmscnvrt.o -c vendor/src/cmscnvrt.c
```

Working directory: `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I vendor/include -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/lcms2-sys-291f8ed5f45995e7/out/49c72391db7e6a2b-cmserr.o -c vendor/src/cmserr.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
