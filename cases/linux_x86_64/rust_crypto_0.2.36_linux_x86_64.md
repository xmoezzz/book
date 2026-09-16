# `rust-crypto` `0.2.36`

Platform: Linux x86_64

## `/work/target/debug/build/rust-crypto-55f19f8fbef39c05/out/lib_rust_crypto_helpers.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/aesni_helpers.c`
* `/work/src/util_helpers.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -m64 -Wall -Wextra -o /work/target/debug/build/rust-crypto-55f19f8fbef39c05/out/src/util_helpers.o -c src/util_helpers.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu src/util_helpers.c -quiet -dumpdir /work/target/debug/build/rust-crypto-55f19f8fbef39c05/out/src/ -dumpbase util_helpers.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -O0 -Wall -Wextra -ffunction-sections ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -m64 -Wall -Wextra -o /work/target/debug/build/rust-crypto-55f19f8fbef39c05/out/src/aesni_helpers.o -c src/aesni_helpers.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu src/aesni_helpers.c -quiet -dumpdir /work/target/debug/build/rust-crypto-55f19f8fbef39c05/out/src/ -dumpbase aesni_helpers.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -O0 -Wall -Wextra -ffunction-sections ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -m64 -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar crs <static library> <object files>
```
