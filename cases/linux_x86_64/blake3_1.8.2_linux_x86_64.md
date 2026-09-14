# `blake3` `1.8.2`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1841450

Build-script executable: `/work/target/debug/build/blake3-824c7a312e26255f/build_script_build-824c7a312e26255f`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

### Other root-owned linker native-library inputs

#### Linker process 1841696

Link output: `/work/target/debug/build/blake3-6b0b720cd86fdbf5/out/flag_check`

Working directory: `/work/target/debug/build/blake3-6b0b720cd86fdbf5/out`

```text
/work/.tmp/native-trace-1836714-1784021418300/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccy0CLyH.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o /work/target/debug/build/blake3-6b0b720cd86fdbf5/out/flag_check /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccjoN9pW.o --trace -Map /work/.tmp/native-trace-link-cc-1841668-1784021424620518522.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1841668

Link output: `/work/target/debug/build/blake3-6b0b720cd86fdbf5/out/flag_check`

Working directory: `/work/target/debug/build/blake3-6b0b720cd86fdbf5/out`

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -m64 -Wall -Wextra -mavx512f -o /work/target/debug/build/blake3-6b0b720cd86fdbf5/out/flag_check /work/target/debug/build/blake3-6b0b720cd86fdbf5/out/flag_check.c
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/blake3-6b0b720cd86fdbf5/out/libblake3_sse2_sse41_avx2_assembly.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/c`

### Source file examples

* `/work/c/blake3_avx2_x86-64_unix.S`
* `/work/c/blake3_sse2_x86-64_unix.S`
* `/work/c/blake3_sse41_x86-64_unix.S`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -std=c11 -o /work/target/debug/build/blake3-6b0b720cd86fdbf5/out/b8423798394d5395-blake3_sse2_x86-64_unix.o -c c/blake3_sse2_x86-64_unix.S
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -E -lang-asm -quiet -imultiarch x86_64-linux-gnu c/blake3_sse2_x86-64_unix.S -m64 -mtune=generic -march=x86-64 -std=c11 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -gdwarf-4 -fworking-directory -O0 ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -std=c11 -o /work/target/debug/build/blake3-6b0b720cd86fdbf5/out/b8423798394d5395-blake3_sse41_x86-64_unix.o -c c/blake3_sse41_x86-64_unix.S
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -E -lang-asm -quiet -imultiarch x86_64-linux-gnu c/blake3_sse41_x86-64_unix.S -m64 -mtune=generic -march=x86-64 -std=c11 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -gdwarf-4 -fworking-directory -O0 ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -std=c11 -o /work/target/debug/build/blake3-6b0b720cd86fdbf5/out/b8423798394d5395-blake3_avx2_x86-64_unix.o -c c/blake3_avx2_x86-64_unix.S
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -std=c11 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
