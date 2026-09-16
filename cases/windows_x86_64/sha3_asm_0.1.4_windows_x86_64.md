# `sha3-asm` `0.1.4`

Platform: Windows x86_64

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/libkeccak.a`

### Source origin

* under build output directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/target/debug/build/sha3-asm-6a2ab6cd2950d00e/out`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/target/debug/build/sha3-asm-6a2ab6cd2950d00e/out`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm`

### Compilation

```text
ml64 -nologo -Zi -D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze -DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze -D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext -DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext -D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb -DSHA3_absorb=KECCAK_ASM_SHA3_absorb -D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext -DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
