# `ring` `0.17.14`

Platform: Linux x86_64

## `/work/target/debug/build/ring-92e8a52839e59707/out/libring_core_0_17_14_.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work`

### Source file examples

* `/work/crypto/cpu_intel.c`
* `/work/crypto/crypto.c`
* `/work/crypto/curve25519/curve25519.c`
* `/work/crypto/curve25519/curve25519_64_adx.c`
* `/work/crypto/fipsmodule/aes/aes_nohw.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion -Wmissing-field-initializers -Wmissing-include-dirs -Wnested-externs -Wredundant-decls -Wshadow -Wsign-compare -Wsign-conversion -Wstrict-prototypes -Wundef -Wuninitialized -g3 -DNDEBUG -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```

## `/work/target/debug/build/ring-92e8a52839e59707/out/libring_core_0_17_14__test.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/crypto`

### Source file examples

* `/work/crypto/constant_time_test.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion -Wmissing-field-initializers -Wmissing-include-dirs -Wnested-externs -Wredundant-decls -Wshadow -Wsign-compare -Wsign-conversion -Wstrict-prototypes -Wundef -Wuninitialized -g3 -DNDEBUG -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
