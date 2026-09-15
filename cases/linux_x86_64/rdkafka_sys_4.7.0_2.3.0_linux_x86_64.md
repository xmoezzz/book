# `rdkafka-sys` `4.7.0+2.3.0`

Platform: Linux x86_64

## Build-level coding evidence

### Source acquisition

Working directory: `/work`

```text
internal_build_script_archive_output
```

Working directory: `/work`

```text
internal_build_script_archive_output
```

Working directory: `/work`

```text
internal_build_script_archive_output
```

Working directory: `/work`

```text
internal_build_script_archive_output
```

### pkg-config / pkgconf

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
pkg-config --version
```

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
pkg-config --short-errors --cflags zlib
```

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
pkg-config --short-errors --libs zlib
```

### Build-script executable native dependencies

#### Linker process 1942145

Build-script executable: `/work/target/debug/build/rdkafka-sys-aad4a83e051af4ac/build_script_build-aad4a83e051af4ac`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

### Other root-owned linker native-library inputs

#### Linker process 1950323

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpf5ifGN.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccTFEe9q.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpf5ifGN.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccqtCJiq.o --trace -Map /work/.tmp/native-trace-link-cc-1950259-1784021652254953168.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 1950259

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpf5ifGN.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -Wall -Werror _mkltmpf5ifGN.c -o _mkltmpf5ifGN.c.o -fPIC
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1950526

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpT0Iurj.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cc4a1O7i.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -o _mkltmpT0Iurj.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccv32eKn.o -soname mkltest.0 --trace -Map /work/.tmp/native-trace-link-cc-1950487-1784021652562307086.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1950487

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpT0Iurj.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Werror _mkltmpT0Iurj.c -o _mkltmpT0Iurj.c.o -shared -Wl,-soname,mkltest.0
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1950709

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpH0K65u.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccZCyasE.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -o _mkltmpH0K65u.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccn7D6oZ.o --version-script=_mkltmpjcWVFP --trace -Map /work/.tmp/native-trace-link-cc-1950680-1784021652824867586.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1950680

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpH0K65u.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Werror _mkltmpH0K65u.c -o _mkltmpH0K65u.c.o -shared -Wl,--version-script=_mkltmpjcWVFP
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1950872

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpBBHSS1.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cc4W9INN.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpBBHSS1.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/cctpIF9W.o --trace -Map /work/.tmp/native-trace-link-cc-1950791-1784021652972489855.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 1950791

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpBBHSS1.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Werror _mkltmpBBHSS1.c -o _mkltmpBBHSS1.c.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1950936

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpF0wrQk.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccmKJGhe.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpF0wrQk.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccL3rCG6.o --trace -Map /work/.tmp/native-trace-link-cc-1950902-1784021653222132800.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 1950902

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpF0wrQk.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Werror _mkltmpF0wrQk.c -o _mkltmpF0wrQk.c.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951130

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmppAxNJW.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccbHbRM9.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmppAxNJW.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccb2MLm9.o --trace -Map /work/.tmp/native-trace-link-cc-1950964-1784021653392612673.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

* `(socket@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1950964

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmppAxNJW.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmppAxNJW.c -o _mkltmppAxNJW.c.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951248

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpj9RMpU.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccweEWl2.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpj9RMpU.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccIzVQl9.o -lrt --trace -Map /work/.tmp/native-trace-link-cc-1951208-1784021653834349853.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951208

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpj9RMpU.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpj9RMpU.c -o _mkltmpj9RMpU.c.o -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951374

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpIUinKf.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cca8Mpg7.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpIUinKf.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/cc8u7a0d.o -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1951347-1784021654137782314.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951347

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpIUinKf.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpIUinKf.c -o _mkltmpIUinKf.c.o -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951491

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmp3DfT6m.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cckQErY2.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmp3DfT6m.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccBV1SbN.o -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1951452-1784021654332977898.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(thrd_create@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951452

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmp3DfT6m.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmp3DfT6m.c -o _mkltmp3DfT6m.c.o -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951739

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpLNt9bZ.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccafWJhb.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpLNt9bZ.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccxMiz27.o -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1951674-1784021654727306983.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(dlclose@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951674

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpLNt9bZ.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpLNt9bZ.c -o _mkltmpLNt9bZ.c.o -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951926

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpmt4Sl2.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccADDCsr.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpmt4Sl2.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/cc7Xkw3t.o -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1951812-1784021655060500821.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(inflate` (dynamic_library)
* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951812

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpmt4Sl2.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpmt4Sl2.c -o _mkltmpmt4Sl2.c.o -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1952006

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpFsYhJc.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cc5ALAdC.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpFsYhJc.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccuWD6Dc.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1951989-1784021655470940592.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1951989

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpFsYhJc.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpFsYhJc.c -o _mkltmpFsYhJc.c.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1952110

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpxTNvz9.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cclxiIlJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpxTNvz9.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccgl9jUK.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1952082-1784021655704818960.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(syslog@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1952082

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpxTNvz9.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpxTNvz9.c -o _mkltmpxTNvz9.c.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1952382

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmp77tsQV.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccNynM64.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmp77tsQV.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccuVS7Nz.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1952229-1784021656007965345.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1952229

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmp77tsQV.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmp77tsQV.c -o _mkltmp77tsQV.c.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1952495

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpOHlxMY.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccui1UWo.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpOHlxMY.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccv6fy6J.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1952460-1784021656446102440.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(regfree@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1952460

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpOHlxMY.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpOHlxMY.c -o _mkltmpOHlxMY.c.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1952753

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpj7Npul.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccdoTQQC.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpj7Npul.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccMSFEwW.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1952569-1784021656664960668.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(rand_r@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1952569

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpj7Npul.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpj7Npul.c -o _mkltmpj7Npul.c.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1953004

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpk5LTud.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccRLfjKc.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpk5LTud.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccMmMM6B.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1952965-1784021657378168875.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(strndup@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1952965

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpk5LTud.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpk5LTud.c -o _mkltmpk5LTud.c.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1953116

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmp4FyegV.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cc8nvcTr.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmp4FyegV.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/cczpbQGB.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1953078-1784021657769297486.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__xpg_strerror_r@@GLIBC_2.3.4` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1953078

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmp4FyegV.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmp4FyegV.c -o _mkltmp4FyegV.c.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1953220

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmppiWhsF.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccGfZYdJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmppiWhsF.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccBvb5ym.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1953198-1784021658097911421.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(strcasestr@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1953198

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmppiWhsF.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmppiWhsF.c -o _mkltmppiWhsF.c.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1953333

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpCtDfqn.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccPPxsUn.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpCtDfqn.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/cc3NFHDm.o -lpthread -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1953294-1784021658321597176.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(pthread_self@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1953294

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpCtDfqn.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpCtDfqn.c -o _mkltmpCtDfqn.c.o -D_GNU_SOURCE -lpthread -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1953392

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpAeWgzJ.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccbDLIM1.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o _mkltmpAeWgzJ.c.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccz0SQRA.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1953376-1784021658451912005.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(getrusage@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1953376

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/_mkltmpAeWgzJ.c.o`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

```text
cc -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpAeWgzJ.c -o _mkltmpAeWgzJ.c.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1980097

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/librdkafka.so.1`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccRCKzWd.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -o librdkafka.so.1 /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. -soname librdkafka.so.1 --version-script=librdkafka.lds rdkafka.o rdkafka_broker.o rdkafka_msg.o rdkafka_topic.o rdkafka_conf.o rdkafka_timer.o rdkafka_offset.o rdkafka_transport.o rdkafka_buf.o rdkafka_queue.o rdkafka_op.o rdkafka_request.o rdkafka_cgrp.o rdkafka_pattern.o rdkafka_partition.o rdkafka_subscription.o rdkafka_assignment.o rdkafka_assignor.o rdkafka_range_assignor.o rdkafka_roundrobin_assignor.o rdkafka_sticky_assignor.o rdkafka_feature.o rdcrc32.o crc32c.o rdmurmur2.o rdfnv1a.o cJSON.o rdaddr.o rdrand.o rdlist.o tinycthread.o tinycthread_extra.o rdlog.o rdstring.o rdkafka_event.o rdkafka_metadata.o rdregex.o rdports.o rdkafka_metadata_cache.o rdavl.o rdkafka_sasl.o rdkafka_sasl_plain.o rdkafka_interceptor.o rdkafka_msgset_writer.o rdkafka_msgset_reader.o rdkafka_header.o rdkafka_admin.o rdkafka_aux.o rdkafka_background.o rdkafka_idempotence.o rdkafka_cert.o rdkafka_txnmgr.o rdkafka_coord.o rdbase64.o rdvarint.o rdbuf.o rdmap.o rdunittest.o rdkafka_mock.o rdkafka_mock_handlers.o rdkafka_mock_cgrp.o rdkafka_error.o rdkafka_fetcher.o snappy.o rdgz.o rdhdrhistogram.o rdkafka_lz4.o rdxxhash.o lz4.o lz4frame.o lz4hc.o rddl.o rdkafka_plugin.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /work/.tmp/native-trace-link-cc-1980082-1784021738008821407.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1980082

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/librdkafka.so.1`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src`

```text
cc -shared -Wl,-soname,librdkafka.so.1 -Wl,--version-script=librdkafka.lds rdkafka.o rdkafka_broker.o rdkafka_msg.o rdkafka_topic.o rdkafka_conf.o rdkafka_timer.o rdkafka_offset.o rdkafka_transport.o rdkafka_buf.o rdkafka_queue.o rdkafka_op.o rdkafka_request.o rdkafka_cgrp.o rdkafka_pattern.o rdkafka_partition.o rdkafka_subscription.o rdkafka_assignment.o rdkafka_assignor.o rdkafka_range_assignor.o rdkafka_roundrobin_assignor.o rdkafka_sticky_assignor.o rdkafka_feature.o rdcrc32.o crc32c.o rdmurmur2.o rdfnv1a.o cJSON.o rdaddr.o rdrand.o rdlist.o tinycthread.o tinycthread_extra.o rdlog.o rdstring.o rdkafka_event.o rdkafka_metadata.o rdregex.o rdports.o rdkafka_metadata_cache.o rdavl.o rdkafka_sasl.o rdkafka_sasl_plain.o rdkafka_interceptor.o rdkafka_msgset_writer.o rdkafka_msgset_reader.o rdkafka_header.o rdkafka_admin.o rdkafka_aux.o rdkafka_background.o rdkafka_idempotence.o rdkafka_cert.o rdkafka_txnmgr.o rdkafka_coord.o rdbase64.o rdvarint.o rdbuf.o rdmap.o rdunittest.o rdkafka_mock.o rdkafka_mock_handlers.o rdkafka_mock_cgrp.o rdkafka_error.o rdkafka_fetcher.o snappy.o rdgz.o rdhdrhistogram.o rdkafka_lz4.o rdxxhash.o lz4.o lz4frame.o lz4hc.o rddl.o rdkafka_plugin.o -o librdkafka.so.1 -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1985124

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/librdkafka++.so.1`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp`

```text
/work/.tmp/native-trace-1939505-1784021635242/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cckpUGJm.res -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -o librdkafka++.so.1 /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L../src -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. -soname librdkafka++.so.1 RdKafka.o ConfImpl.o HandleImpl.o ConsumerImpl.o ProducerImpl.o KafkaConsumerImpl.o TopicImpl.o TopicPartitionImpl.o MessageImpl.o HeadersImpl.o QueueImpl.o MetadataImpl.o -lrdkafka --trace -Map /work/.tmp/native-trace-link-c++-1985113-1784021752698120984.map -lstdc++ -lm -lgcc_s -lc -lgcc_s /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/../src/librdkafka.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libstdc++.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/../src/librdkafka.so` (dynamic_library)
* `../src/librdkafka.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libstdc++.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1985113

Link output: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/librdkafka++.so.1`

Working directory: `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp`

```text
c++ -shared -Wl,-soname,librdkafka++.so.1 RdKafka.o ConfImpl.o HandleImpl.o ConsumerImpl.o ProducerImpl.o KafkaConsumerImpl.o TopicImpl.o TopicPartitionImpl.o MessageImpl.o HeadersImpl.o QueueImpl.o MetadataImpl.o -o librdkafka++.so.1 -L../src -lrdkafka
```

**Linker library inputs**

* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/../src/librdkafka.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libstdc++.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/librdkafka++.a`

### Source origin

* under build output directory `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

### Source directories

* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp`

### Source file examples

* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/ConfImpl.cpp`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/ConsumerImpl.cpp`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/HandleImpl.cpp`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/HeadersImpl.cpp`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/KafkaConsumerImpl.cpp`

### Compilation

```text
c++ -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wno-non-virtual-dtor -c <source> -o <object>
```

### Static library construction

```text
ar rcs <static library> <object files>
```

## `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/librdkafka++.so.1`

### Source origin

* under build output directory `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

### Source directories

* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp`

### Source file examples

* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/ConfImpl.cpp`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/ConsumerImpl.cpp`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/HandleImpl.cpp`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/HeadersImpl.cpp`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/KafkaConsumerImpl.cpp`

### Compilation

```text
c++ -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wno-non-virtual-dtor -c <source> -o <object>
```

### Native linking

```text
c++ -shared <native inputs> -o <native artifact> -L../src -lrdkafka
```

### Linked native libraries

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o (object)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o (object)`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src-cpp/../src/librdkafka.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/libstdc++.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so (dynamic_library)`
* `/lib/x86_64-linux-gnu/libm.so.6 (dynamic_library)`
* `/lib/x86_64-linux-gnu/libmvec.so.1 (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1 (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a (static_library)`

## `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/librdkafka.a`

### Source origin

* under build output directory `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

### Source directories

* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src`

### Source file examples

* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/cJSON.c`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/crc32c.c`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/lz4.c`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/lz4frame.c`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/lz4hc.c`

### Compilation

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -c <source> -o <object>
```

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -O3 -c <source> -o <object>
```

### Static library construction

```text
ar rcs <static library> <object files>
```

## `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/librdkafka.so.1`

### Source origin

* under build output directory `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out`

### Source directories

* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src`

### Source file examples

* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/cJSON.c`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/crc32c.c`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/lz4.c`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/lz4frame.c`
* `/work/target/debug/build/rdkafka-sys-a3bd02638dd1413f/out/src/lz4hc.c`

### Compilation

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -c <source> -o <object>
```

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -O3 -c <source> -o <object>
```

### Native linking

```text
cc -shared <native inputs> -Wl,--version-script=librdkafka.lds -o <native artifact> -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

### Linked native libraries

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o (object)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o (object)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libm.so (dynamic_library)`
* `/lib/x86_64-linux-gnu/libm.so.6 (dynamic_library)`
* `/lib/x86_64-linux-gnu/libmvec.so.1 (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libz.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libdl.a (static_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libpthread.a (static_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/librt.a (static_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a (static_library)`
