# `aws-lc-fips-sys` `0.13.6`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1940168

Build-script executable: `/work/target/debug/build/aws-lc-fips-sys-ab5be45d9d647c65/build_script_main-ab5be45d9d647c65`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

### Other root-owned linker native-library inputs

#### Linker process 1941139

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/CMakeFiles/3.25.1/CompilerIdC`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccadyTGO.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccl8gOW0.o --trace -Map /work/.tmp/native-trace-link-cc-1941126-1784021638633041778.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 1941126

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/CMakeFiles/3.25.1/CompilerIdC`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/cc -ffunction-sections -fdata-sections -fPIC -m64 CMakeCCompilerId.c
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1941359

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/CMakeFiles/CMakeScratch/TryCompile-o3ldPC/cmTC_8797f`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/CMakeFiles/CMakeScratch/TryCompile-o3ldPC`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccVm0sTq.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o cmTC_8797f /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. CMakeFiles/cmTC_8797f.dir/CMakeCCompilerABI.c.o --trace -Map /work/.tmp/native-trace-link-cc-1941351-1784021639029630894.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 1941351

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/CMakeFiles/CMakeScratch/TryCompile-o3ldPC/cmTC_8797f`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/CMakeFiles/CMakeScratch/TryCompile-o3ldPC`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/cc -ffunction-sections -fdata-sections -fPIC -m64 -v CMakeFiles/cmTC_8797f.dir/CMakeCCompilerABI.c.o -o cmTC_8797f
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so` (dynamic_library)

#### Linker process 1941562

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp/cmTC_dfc42`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cc5FEjF4.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o cmTC_dfc42 /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. CMakeFiles/cmTC_dfc42.dir/c11.c.o --trace -Map /work/.tmp/native-trace-link-cc-1941534-1784021639330548217.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 1941534

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp/cmTC_dfc42`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/cc -ffunction-sections -fdata-sections -fPIC -m64 CMakeFiles/cmTC_dfc42.dir/c11.c.o -o cmTC_dfc42
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1941804

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp/cmTC_03117`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccx2YCZe.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o cmTC_03117 /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. CMakeFiles/cmTC_03117.dir/stdalign_check.c.o --trace -Map /work/.tmp/native-trace-link-cc-1941796-1784021639796468407.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 1941796

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp/cmTC_03117`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/cc -ffunction-sections -fdata-sections -fPIC -m64 -Wredundant-decls -Wextra -Wunused -Wcomment -Wchar-subscripts -Wuninitialized -Wshadow -Wwrite-strings -Wformat-security -Wunused-result -Wno-overlength-strings -Wno-cast-function-type -Wall -fvisibility=hidden -fno-common -Wno-c11-extensions -Wvla -Wtype-limits -Wno-unused-parameter -Werror -Wformat=2 -Wsign-compare -Wmissing-field-initializers -Wwrite-strings -ggdb -Wno-free-nonheap-object -Wmissing-braces -Wimplicit-fallthrough -Wmissing-prototypes -Wold-style-definition -Wstrict-prototypes CMakeFiles/cmTC_03117.dir/stdalign_check.c.o -o cmTC_03117
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1941935

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp/cmTC_f9eee`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccVCTvGr.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o cmTC_f9eee /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. CMakeFiles/cmTC_f9eee.dir/builtin_swap_check.c.o --trace -Map /work/.tmp/native-trace-link-cc-1941932-1784021640035141711.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 1941932

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp/cmTC_f9eee`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/cc -ffunction-sections -fdata-sections -fPIC -m64 -Wredundant-decls -Wextra -Wunused -Wcomment -Wchar-subscripts -Wuninitialized -Wshadow -Wwrite-strings -Wformat-security -Wunused-result -Wno-overlength-strings -Wno-cast-function-type -Wall -fvisibility=hidden -fno-common -Wno-c11-extensions -Wvla -Wtype-limits -Wno-unused-parameter -Werror -Wformat=2 -Wsign-compare -Wmissing-field-initializers -Wwrite-strings -ggdb -Wno-free-nonheap-object -Wmissing-braces -Wimplicit-fallthrough -Wmissing-prototypes -Wold-style-definition -Wstrict-prototypes CMakeFiles/cmTC_f9eee.dir/builtin_swap_check.c.o -o cmTC_f9eee
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1942122

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp/cmTC_351d7`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cccR9ygd.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o cmTC_351d7 /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. CMakeFiles/cmTC_351d7.dir/linux_u32.c.o --trace -Map /work/.tmp/native-trace-link-cc-1942103-1784021640332787655.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 1942103

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp/cmTC_351d7`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/CMakeFiles/CMakeTmp`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/cc -ffunction-sections -fdata-sections -fPIC -m64 -Wredundant-decls -Wextra -Wunused -Wcomment -Wchar-subscripts -Wuninitialized -Wshadow -Wwrite-strings -Wformat-security -Wunused-result -Wno-overlength-strings -Wno-cast-function-type -Wall -fvisibility=hidden -fno-common -Wno-c11-extensions -Wvla -Wtype-limits -Wno-unused-parameter -Werror -Wformat=2 -Wsign-compare -Wmissing-field-initializers -Wwrite-strings -ggdb -Wno-free-nonheap-object -Wmissing-braces -Wimplicit-fallthrough -Wmissing-prototypes -Wold-style-definition -Wstrict-prototypes CMakeFiles/cmTC_351d7.dir/linux_u32.c.o -o cmTC_351d7
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1944678

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/CMakeFiles/CMakeScratch/TryCompile-vbYXUY/cmTC_22ce8`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/CMakeFiles/CMakeScratch/TryCompile-vbYXUY`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cciZGsxD.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o cmTC_22ce8 /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. CMakeFiles/cmTC_22ce8.dir/src.c.o --trace -Map /work/.tmp/native-trace-link-cc-1944673-1784021643439006439.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

* `(pthread_exit@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1944673

Link output: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/CMakeFiles/CMakeScratch/TryCompile-vbYXUY/cmTC_22ce8`

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/CMakeFiles/CMakeScratch/TryCompile-vbYXUY`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/cc -ffunction-sections -fdata-sections -fPIC -m64 -Wredundant-decls -Wextra -Wunused -Wcomment -Wchar-subscripts -Wuninitialized -Wshadow -Wwrite-strings -Wformat-security -Wunused-result -Wno-overlength-strings -Wno-cast-function-type -Wall -fvisibility=hidden -fno-common -Wno-c11-extensions -Wvla -Wtype-limits -Wno-unused-parameter -Werror -Wformat=2 -Wsign-compare -Wmissing-field-initializers -Wwrite-strings -ggdb -Wno-free-nonheap-object -Wmissing-braces -Wimplicit-fallthrough -Wmissing-prototypes -Wold-style-definition -Wstrict-prototypes -DAWS_LC_STDALIGN_AVAILABLE -DAWS_LC_BUILTIN_SWAP_SUPPORTED -DAWS_LC_URANDOM_U32 -Wshadow -D_XOPEN_SOURCE=700 CMakeFiles/cmTC_22ce8.dir/src.c.o -o cmTC_22ce8
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/artifacts/libaws_lc_fips_0_13_6_rust_wrapper.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work`

### Source file examples

* `/work/rust_wrapper.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -DBORINGSSL_PREFIX=aws_lc_fips_0_13_6 -I/work/include -I/work/aws-lc/include -ffunction-sections -fdata-sections -fPIC -m64 -g -MD -MT CMakeFiles/rust_wrapper.dir/rust_wrapper.c.o -MF CMakeFiles/rust_wrapper.dir/rust_wrapper.c.o.d -o CMakeFiles/rust_wrapper.dir/rust_wrapper.c.o -c /work/rust_wrapper.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/include -I /work/aws-lc/include -imultiarch x86_64-linux-gnu -MD CMakeFiles/rust_wrapper.dir/rust_wrapper.c.d -MF CMakeFiles/rust_wrapper.dir/rust_wrapper.c.o.d -MT CMakeFiles/rust_wrapper.dir/rust_wrapper.c.o -D BORINGSSL_PREFIX=aws_lc_fips_0_13_6 /work/rust_wrapper.c -quiet -dumpdir CMakeFiles/rust_wrapper.dir/ ...
```

### Compilation

```text
cc -DBORINGSSL_PREFIX=aws_lc_fips_0_13_6 -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -g -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

### Static library construction

```text
ar qc <static library> <object files>
```

## `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/../../artifacts/libaws_lc_fips_0_13_6_crypto.a`

### Source origin

* under crate source directory `/work`
* under build output directory `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out`

### Source directories

* `/work`

### Source file examples

* `/work/aws-lc/crypto/asn1/a_bitstr.c`
* `/work/aws-lc/crypto/asn1/a_bool.c`
* `/work/aws-lc/crypto/asn1/a_d2i_fp.c`
* `/work/aws-lc/crypto/asn1/a_dup.c`
* `/work/aws-lc/crypto/asn1/a_gentm.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/symbol_prefix_include -I/work/aws-lc/include -ffunction-sections -fdata-sections -fPIC -m64 -Wno-newline-eof -Wa,--noexecstack -Wa,-g -g -fPIC -o CMakeFiles/crypto_objects.dir/chacha/chacha-x86_64.S.o -c /work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/chacha/chacha-x86_64.S
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -E -lang-asm -quiet -I /work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/symbol_prefix_include -I /work/aws-lc/include -imultiarch x86_64-linux-gnu -D BORINGSSL_FIPS -D BORINGSSL_IMPLEMENTATION -D FIPS_ENTROPY_SOURCE_PASSIVE /work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/chacha/chacha-x86_64.S -m64 -mtune=generic -march=x86-64 ...
```

Working directory: `/work`

```text
/usr/bin/cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/symbol_prefix_include -I/work/aws-lc/include -ffunction-sections -fdata-sections -fPIC -m64 -Wno-newline-eof -Wa,--noexecstack -Wa,-g -g -fPIC -o CMakeFiles/crypto_objects.dir/cipher_extra/aes128gcmsiv-x86_64.S.o -c /work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/cipher_extra/aes128gcmsiv-x86_64.S
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -E -lang-asm -quiet -I /work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/symbol_prefix_include -I /work/aws-lc/include -imultiarch x86_64-linux-gnu -D BORINGSSL_FIPS -D BORINGSSL_IMPLEMENTATION -D FIPS_ENTROPY_SOURCE_PASSIVE /work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/cipher_extra/aes128gcmsiv-x86_64.S -m64 -mtune=generic -march=x86-64 ...
```

Working directory: `/work`

```text
/usr/bin/cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/symbol_prefix_include -I/work/aws-lc/include -ffunction-sections -fdata-sections -fPIC -m64 -Wno-newline-eof -Wa,--noexecstack -Wa,-g -g -fPIC -o CMakeFiles/crypto_objects.dir/cipher_extra/chacha20_poly1305_x86_64.S.o -c /work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/cipher_extra/chacha20_poly1305_x86_64.S
```

### Compilation

```text
cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -Wredundant-decls -Wextra -Wunused -Wcomment -Wchar-subscripts -Wuninitialized -Wshadow -Wwrite-strings -Wformat-security -Wunused-result -Wno-overlength-strings -Wno-cast-function-type -Wall -fvisibility=hidden -fno-common -Wno-c11-extensions -Wvla -Wtype-limits -Wno-unused-parameter -Werror -Wformat=2 -Wsign-compare -Wmissing-field-initializers -Wwrite-strings -ggdb -Wno-free-nonheap-object -Wmissing-braces -Wimplicit-fallthrough -Wmissing-prototypes -Wold-style-definition -Wstrict-prototypes -DAWS_LC_STDALIGN_AVAILABLE -DAWS_LC_BUILTIN_SWAP_SUPPORTED -DAWS_LC_URANDOM_U32 -Wshadow -D_XOPEN_SOURCE=700 -g -fPIC -std=gnu11 -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

```text
cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -Wno-newline-eof -Wa,--noexecstack -Wa,-g -g -fPIC -o <object> -c <source>
```

### Static library construction

```text
ar qc <static library> <object files>
```

## `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/fipsmodule/libbcm_c_generated_asm.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/aws-lc/crypto/fipsmodule`

### Source file examples

* `/work/aws-lc/crypto/fipsmodule/bcm.c`

### Compilation

```text
cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -Wredundant-decls -Wextra -Wunused -Wcomment -Wchar-subscripts -Wuninitialized -Wshadow -Wwrite-strings -Wformat-security -Wunused-result -Wno-overlength-strings -Wno-cast-function-type -Wall -fvisibility=hidden -fno-common -Wno-c11-extensions -Wvla -Wtype-limits -Wno-unused-parameter -Werror -Wformat=2 -Wsign-compare -Wmissing-field-initializers -Wwrite-strings -ggdb -Wno-free-nonheap-object -Wmissing-braces -Wimplicit-fallthrough -Wmissing-prototypes -Wold-style-definition -Wstrict-prototypes -DAWS_LC_STDALIGN_AVAILABLE -DAWS_LC_BUILTIN_SWAP_SUPPORTED -DAWS_LC_URANDOM_U32 -Wshadow -D_XOPEN_SOURCE=700 -g -fPIC -S -std=gnu11 -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

### Static library construction

```text
ar qc <static library> <object files>
```

## `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/fipsmodule/libbcm_hashunset.a`

### Source origin

* under build output directory `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out`

### Source directories

* `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/fipsmodule`

### Source file examples

* `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/fipsmodule/bcm-delocated.S`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/symbol_prefix_include -I/work/aws-lc/include -ffunction-sections -fdata-sections -fPIC -m64 -Wno-newline-eof -Wa,--noexecstack -Wa,-g -g -fPIC -o CMakeFiles/bcm_hashunset.dir/bcm-delocated.S.o -c /work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/fipsmodule/bcm-delocated.S
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -E -lang-asm -quiet -I /work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/symbol_prefix_include -I /work/aws-lc/include -imultiarch x86_64-linux-gnu -D BORINGSSL_FIPS -D BORINGSSL_IMPLEMENTATION -D FIPS_ENTROPY_SOURCE_PASSIVE /work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/fipsmodule/bcm-delocated.S -m64 -mtune=generic -march=x86-64 ...
```

### Compilation

```text
cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -Wno-newline-eof -Wa,--noexecstack -Wa,-g -g -fPIC -o <object> -c <source>
```

### Static library construction

```text
ar qc <static library> <object files>
```
