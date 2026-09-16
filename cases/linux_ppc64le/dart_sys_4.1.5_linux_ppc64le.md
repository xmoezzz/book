# `dart-sys` `4.1.5`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/dart-sys-ca281e5e289bfbbd/out/libdart_api_dl.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5`

### Source directories

* `/tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5/dart-sdk/include`

### Source file examples

* `/tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5/dart-sdk/include/dart_api_dl.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5/dart-sdk/include -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/dart-sys-ca281e5e289bfbbd/out/248f927bf32daba4-dart_api_dl.o -c /tmp/crate-build-ppc64le-65qsqvkh/src/dart-sys-4.1.5/dart-sdk/include/dart_api_dl.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
