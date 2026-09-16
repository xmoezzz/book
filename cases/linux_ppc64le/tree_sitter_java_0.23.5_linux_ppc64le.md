# `tree-sitter-java` `0.23.5`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5`

### Source directories

* `/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5/src`

### Source file examples

* `/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5/src/parser.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o -c src/parser.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
