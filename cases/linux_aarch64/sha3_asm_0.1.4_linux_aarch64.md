# `sha3-asm` `0.1.4`

Platform: Linux aarch64

## Submodule

Repository: `https://github.com/danipopes/keccak-asm`
Crate release commit: `7d801fae4b70ad79b57f55fbebf448783db8423e`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `sha3-asm`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `sha3-asm/cryptogams`

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
