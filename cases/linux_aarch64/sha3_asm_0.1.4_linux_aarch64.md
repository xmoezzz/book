# `sha3-asm` `0.1.4`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/sha3-asm-c89dadc71981b926/out/libkeccak.a`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-b2pmpbr7/src/sha3-asm-0.1.4`

```text
perl cryptogams/arm/keccak1600-armv8.pl linux64 /target/aarch64-unknown-linux-gnu/debug/build/sha3-asm-c89dadc71981b926/out/keccak1600-armv8.S
```

Working directory: `/tmp/crate-build-aarch64-b2pmpbr7/src/sha3-asm-0.1.4`

```text
/usr/bin/perl cryptogams/arm/keccak1600-armv8.pl linux64 /target/aarch64-unknown-linux-gnu/debug/build/sha3-asm-c89dadc71981b926/out/keccak1600-armv8.S
```

Working directory: `/tmp/crate-build-aarch64-b2pmpbr7/src/sha3-asm-0.1.4`

```text
/usr/bin/perl cryptogams/arm/arm-xlate.pl linux64 /target/aarch64-unknown-linux-gnu/debug/build/sha3-asm-c89dadc71981b926/out/keccak1600-armv8.S
```

### Static library construction

```text
ar cqD <static library> <object files>
```
