# `sha3-asm` `0.1.4`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/danipopes/keccak-asm`
Crate release commit: `7d801fae4b70ad79b57f55fbebf448783db8423e`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `sha3-asm`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `sha3-asm/cryptogams`

## `/work/target/debug/build/sha3-asm-52088b83cc6ca76b/out/libkeccak.a`

### Source origin

* under build output directory `/work/target/debug/build/sha3-asm-52088b83cc6ca76b/out`

### Source directories

* `/work/target/debug/build/sha3-asm-52088b83cc6ca76b/out`

### Source file examples

* `/work/target/debug/build/sha3-asm-52088b83cc6ca76b/out/keccak1600-x86_64.S`

### Source preparation

Working directory: `/work`

```text
perl cryptogams/x86_64/keccak1600-x86_64.pl elf target/debug/build/sha3-asm-52088b83cc6ca76b/out/keccak1600-x86_64.S
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze -DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze -D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext -DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext -D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb -DSHA3_absorb=KECCAK_ASM_SHA3_absorb -D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext -DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
