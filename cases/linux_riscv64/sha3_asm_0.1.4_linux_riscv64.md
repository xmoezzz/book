# `sha3-asm` `0.1.4`

Platform: Linux riscv64

## Submodule

Repository: `https://github.com/danipopes/keccak-asm`
Crate release commit: `7d801fae4b70ad79b57f55fbebf448783db8423e`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `sha3-asm`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `sha3-asm/cryptogams`

## `/target/riscv64gc-unknown-linux-gnu/debug/build/sha3-asm-a6f1b14f02f914a9/out/libkeccak.a`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-z_5xz0ah/src/sha3-asm-0.1.4`

```text
perl cryptogams/riscv/keccak1600-riscv.pl 64 /target/riscv64gc-unknown-linux-gnu/debug/build/sha3-asm-a6f1b14f02f914a9/out/keccak1600-riscv.S
```

Working directory: `/tmp/crate-build-riscv64-z_5xz0ah/src/sha3-asm-0.1.4`

```text
/usr/bin/perl cryptogams/riscv/keccak1600-riscv.pl 64 /target/riscv64gc-unknown-linux-gnu/debug/build/sha3-asm-a6f1b14f02f914a9/out/keccak1600-riscv.S
```

### Static library construction

```text
ar cqD <static library> <object files>
```
