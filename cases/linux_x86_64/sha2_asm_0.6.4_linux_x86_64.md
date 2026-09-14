# `sha2-asm` `0.6.4`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1921774

Build-script executable: `/work/target/debug/build/sha2-asm-5495a15eba38c8f4/build_script_build-5495a15eba38c8f4`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/sha2-asm-71feed0f0fa0f467/out/libsha256.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/sha256_x64.S`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -c -o /work/target/debug/build/sha2-asm-71feed0f0fa0f467/out/81a71fbc30f7fcce-sha256_x64.o -c src/sha256_x64.S
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -E -lang-asm -quiet -imultiarch x86_64-linux-gnu src/sha256_x64.S -m64 -mtune=generic -march=x86-64 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -g -gdwarf-4 -fworking-directory -O0 ...
```

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

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -c -o /work/target/debug/build/sha2-asm-71feed0f0fa0f467/out/81a71fbc30f7fcce-sha512_x64.o -c src/sha512_x64.S
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -E -lang-asm -quiet -imultiarch x86_64-linux-gnu src/sha512_x64.S -m64 -mtune=generic -march=x86-64 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -g -gdwarf-4 -fworking-directory -O0 ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -c -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
