# `sha2-asm` `0.6.4`

Platform: Linux x86_64

## `/work/target/debug/build/sha2-asm-71feed0f0fa0f467/out/libsha256.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/sha256_x64.S`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -c -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```

## `/work/target/debug/build/sha2-asm-71feed0f0fa0f467/out/libsha512.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/sha512_x64.S`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -c -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
