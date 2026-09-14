# `tree-sitter` `0.25.10`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 2105622

Build-script executable: `/work/target/debug/build/tree-sitter-5553cba9fa271497/build_script_build-5553cba9fa271497`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

### Other root-owned linker native-library inputs

#### Linker process 2105688

Link output: `/work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check`

Working directory: `/work`

```text
/work/.tmp/native-trace-2097671-1784022047870/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cckH5eGK.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/cckZvyRb.o --trace -Map /work/.tmp/native-trace-link-cc-2105677-1784022068278129261.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 2105677

Link output: `/work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check`

Working directory: `/work`

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -m64 -Wall -Wextra -std=c11 -o /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check.c
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 2105813

Link output: `/work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check`

Working directory: `/work`

```text
/work/.tmp/native-trace-2097671-1784022047870/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccAsMbnF.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccyjZH02.o --trace -Map /work/.tmp/native-trace-link-cc-2105702-1784022068431239139.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 2105702

Link output: `/work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check`

Working directory: `/work`

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -m64 -Wall -Wextra -fvisibility=hidden -o /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check.c
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 2105829

Link output: `/work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check`

Working directory: `/work`

```text
/work/.tmp/native-trace-2097671-1784022047870/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/cc2auwQG.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccNWJMle.o --trace -Map /work/.tmp/native-trace-link-cc-2105824-1784022068620942302.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 2105824

Link output: `/work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check`

Working directory: `/work`

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -m64 -Wall -Wextra -Wshadow -o /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check.c
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 2105843

Link output: `/work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check`

Working directory: `/work`

```text
/work/.tmp/native-trace-2097671-1784022047870/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccXfOUYF.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccwRS6q7.o --trace -Map /work/.tmp/native-trace-link-cc-2105837-1784022068706645940.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 2105837

Link output: `/work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check`

Working directory: `/work`

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -m64 -Wall -Wextra -Wno-unused-parameter -o /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check.c
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 2105859

Link output: `/work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check`

Working directory: `/work`

```text
/work/.tmp/native-trace-2097671-1784022047870/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccqlEHmE.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccEawYB2.o --trace -Map /work/.tmp/native-trace-link-cc-2105853-1784022068839903442.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 2105853

Link output: `/work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check`

Working directory: `/work`

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -m64 -Wall -Wextra -Wno-incompatible-pointer-types -o /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/flag_check.c
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/libtree-sitter.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/lib.c`

### Source preparation

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/src -I /work/src/wasm -I /work/include -imultiarch x86_64-linux-gnu -D _POSIX_C_SOURCE=200112L -D _DEFAULT_SOURCE -D _DARWIN_C_SOURCE /work/src/lib.c -quiet -dumpdir /work/target/debug/build/tree-sitter-907ed277cfed5e0f/out/ ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -I <include directory> -D_POSIX_C_SOURCE=200112L -D_DEFAULT_SOURCE -D_DARWIN_C_SOURCE -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
