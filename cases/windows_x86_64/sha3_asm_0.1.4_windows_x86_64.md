# `sha3-asm` `0.1.4`

Platform: Windows x86_64

## Submodule

Repository: `https://github.com/danipopes/keccak-asm`
Crate release commit: `7d801fae4b70ad79b57f55fbebf448783db8423e`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `sha3-asm`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `sha3-asm/cryptogams`

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/libkeccak.a`

### Source origin

* under build output directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/target/debug/build/sha3-asm-6a2ab6cd2950d00e/out`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/target/debug/build/sha3-asm-6a2ab6cd2950d00e/out`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm`

### Source preparation

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4`

```text
perl cryptogams/x86_64/keccak1600-x86_64.pl masm target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm
```

### Compilation

```text
ml64 -nologo -Zi -D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze -DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze -D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext -DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext -D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb -DSHA3_absorb=KECCAK_ASM_SHA3_absorb -D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext -DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
