# `errno-dragonfly` `0.1.2`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2`

### Source directories

* `/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2/src`

### Source file examples

* `/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2/src/errno.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o -c src/errno.c
```

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
