# `tree-sitter` `0.25.10`

Platform: Linux x86_64

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
