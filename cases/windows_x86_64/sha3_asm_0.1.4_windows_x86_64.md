# `sha3-asm` `0.1.4`

Platform: Windows x86_64

## Build-level coding evidence

### Other root-owned linker native-library inputs

#### Linker process 18704

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4`

```text
C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-uer0obgu\src\sha3-asm-0.1.4\.tmp\native-trace-18356-1783954936947\shims\link.exe @C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-uer0obgu\src\sha3-asm-0.1.4\target\debug\build\sha3-asm-9935574e596261e8\rustctWyxmx\linker-arguments
```

**Linker library inputs**

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/Kits/10/lib/10.0.22621.0/um/x64/kernel32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/Kits/10/lib/10.0.22621.0/um/x64/advapi32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/Kits/10/lib/10.0.22621.0/um/x64/ole32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/Kits/10/lib/10.0.22621.0/um/x64/oleaut32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/Kits/10/lib/10.0.22621.0/um/x64/ntdll.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/Kits/10/lib/10.0.22621.0/um/x64/userenv.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/Kits/10/lib/10.0.22621.0/um/x64/ws2_32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/Kits/10/lib/10.0.22621.0/um/x64/dbghelp.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/msvcrt.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/vcruntime.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/Kits/10/lib/10.0.22621.0/ucrt/x64/ucrt.lib` (library)

**Resolved dynamic-library entries**

* `ADVAPI32.dll` (dynamic_library)
* `KERNEL32.dll` (dynamic_library)
* `OLEAUT32.dll` (dynamic_library)
* `VCRUNTIME140.dll` (dynamic_library)
* `api-ms-win-core-synch-l1-2-0.dll` (dynamic_library)
* `api-ms-win-crt-heap-l1-1-0.dll` (dynamic_library)
* `api-ms-win-crt-locale-l1-1-0.dll` (dynamic_library)
* `api-ms-win-crt-math-l1-1-0.dll` (dynamic_library)
* `api-ms-win-crt-runtime-l1-1-0.dll` (dynamic_library)
* `api-ms-win-crt-stdio-l1-1-0.dll` (dynamic_library)
* `bcryptprimitives.dll` (dynamic_library)
* `ntdll.dll` (dynamic_library)
* `ole32.dll` (dynamic_library)

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
