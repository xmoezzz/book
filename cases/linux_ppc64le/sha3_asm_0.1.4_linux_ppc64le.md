# `sha3-asm` `0.1.4`

Platform: Linux ppc64le

## Submodule

Repository: `https://github.com/danipopes/keccak-asm`
Crate release commit: `7d801fae4b70ad79b57f55fbebf448783db8423e`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `sha3-asm`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `sha3-asm/cryptogams`

## `/target/powerpc64le-unknown-linux-gnu/debug/build/sha3-asm-d32fafdeedb216a5/out/libkeccak.a`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-8snb94_w/src/sha3-asm-0.1.4`

```text
perl cryptogams/ppc/keccak1600-ppc.pl linux64 /target/powerpc64le-unknown-linux-gnu/debug/build/sha3-asm-d32fafdeedb216a5/out/keccak1600-ppc.S
```

Working directory: `/tmp/crate-build-ppc64le-8snb94_w/src/sha3-asm-0.1.4`

```text
/usr/bin/perl cryptogams/ppc/keccak1600-ppc.pl linux64 /target/powerpc64le-unknown-linux-gnu/debug/build/sha3-asm-d32fafdeedb216a5/out/keccak1600-ppc.S
```

Working directory: `/tmp/crate-build-ppc64le-8snb94_w/src/sha3-asm-0.1.4`

```text
/usr/bin/perl cryptogams/ppc/ppc-xlate.pl linux64 /target/powerpc64le-unknown-linux-gnu/debug/build/sha3-asm-d32fafdeedb216a5/out/keccak1600-ppc.S
```

### Static library construction

```text
ar cqD <static library> <object files>
```
