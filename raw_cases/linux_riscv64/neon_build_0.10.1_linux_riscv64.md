# `neon-build` `0.10.1`

Platform: Linux riscv64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned build-level evidence

### Network / source acquisition records

_None._

### pkg-config / pkgconf records

_None._

### Build-script executable native dependencies

These records belong to linker steps that construct the Rust build-script executable. They are retained as coding evidence but are separate from produced native-artifact flows.

### Build-script link records

#### Record 1

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib"
  ],
  "libs": [
    "gcc_s",
    "util",
    "rt",
    "pthread",
    "m",
    "dl",
    "c"
  ],
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

### Build-script resolved-link records

#### Record 1

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC",
    "/target/debug/build/neon-build-e65906ab291905fc",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/lib64"
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib(std-d1237ef7159db0a2.std.e28293b1aa0f68bd-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib(panic_unwind-4be5972b22d3a6da.panic_unwind.d9b2f7d287d2f9d2-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib(object-2a81194c9d07bbf6.object.4f4cc23e276cbdd5-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib(memchr-ea71fa85f6699d6b.memchr.9642f0ce76a98c65-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib(addr2line-a79a8816d9fd6004.addr2line.39b02397e671b2d1-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib(gimli-46dc78dc6a8cb06a.gimli.9d272e8433f81454-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib(rustc_demangle-146c3f1190dee2e2.rustc_demangle.c5a78273c295e539-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib(miniz_oxide-5ad929a15a8e6727.miniz_oxide.b662226d77c6ee8e-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib(adler2-1f570ee5c6635aae.adler2.1d6706876a417dbf-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib(alloc-6e6df4ffe0af4d15.alloc.fdfd2bd8633a6659-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib(core-120cbae4e86ec454.core.c1f1a4ba060b9bfa-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.132.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.187.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.201.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.261.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libm.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libmvec.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libc.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib64",
      "kind": "dynamic_library",
      "path": "/lib64/ld-linux-x86-64.so.2",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o",
      "source": "link_trace"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-711817-1783995938275708739.map",
  "pid": 711817,
  "ppid": 711723,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-711817-1783995938275708739.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Complete analysis record stream

These are the recovered/enriched/generated records actually supplied to native-flow reconstruction.

### Analysis records

#### Record 1

```json
{
  "event": "native_trace_root_context",
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "workspace_root": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
      "name": "neon-build",
      "version": "0.10.1",
      "manifest_path": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1"
    }
  ],
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cwd_prefix"
  }
}
```

#### Record 2

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 711817,
  "ppid": 711723,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "neon-build",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "event_id": "used:cc:b26a5b85a6b58e60:dc81ad933d976d1c:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
  "pid": 711817,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "neon-build",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "event_id": "used:cc:b26a5b85a6b58e60:b69cfa0a6e6d3c6c:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
  "pid": 711817,
  "sha256": "b7cdeae91144abfd6a0bd45b657951c6c3e044b0479fc430a1ba50a77b7e7c55",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "neon-build",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "event_id": "used:cc:b26a5b85a6b58e60:6ea06483502cce10:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
  "pid": 711817,
  "sha256": "8a81f72dac85d8e5b0c8fc2053085e6fa6a451277aac149ff022c9db10b9f0a2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "neon-build",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "event_id": "used:cc:b26a5b85a6b58e60:87ae85677c1f9134:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
  "pid": 711817,
  "sha256": "cb5789a05a4b4d36485425edfde577b1d9c5df9f0cce5d6f6baba9241e5b9471",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "neon-build",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "event_id": "used:cc:b26a5b85a6b58e60:d8181a265005ddd0:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
  "pid": 711817,
  "sha256": "552e84852629177a0e560729a243fa32c1cc010e8b8e42892681b94af3f6868d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "neon-build",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "event_id": "used:cc:b26a5b85a6b58e60:39c241499cfe5df5:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
  "pid": 711817,
  "sha256": "0a2646bbca76ca6f51cdc49d83372ae7ebf0b03bf03d3c47654b7aa892ef1c73",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "neon-build",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "event_id": "used:cc:b26a5b85a6b58e60:5bf41dc1ee611c52:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
  "pid": 711817,
  "sha256": "7f5f25f66313cb930aa311987364b0fea55f1fc6c5bf1d12a673e82c9d3d3a5d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib"
  ],
  "libs": [
    "gcc_s",
    "util",
    "rt",
    "pthread",
    "m",
    "dl",
    "c"
  ],
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "cargo_pkg_name": "neon-build",
  "cargo_pkg_version": "0.10.1",
  "context_path": "/tmp/native-trace-708144-1783995896528/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-708144-1783995896528/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 711817,
  "ppid": 711723,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC",
    "/target/debug/build/neon-build-e65906ab291905fc",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/lib64"
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib(std-d1237ef7159db0a2.std.e28293b1aa0f68bd-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib(panic_unwind-4be5972b22d3a6da.panic_unwind.d9b2f7d287d2f9d2-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib(object-2a81194c9d07bbf6.object.4f4cc23e276cbdd5-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib(memchr-ea71fa85f6699d6b.memchr.9642f0ce76a98c65-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib(addr2line-a79a8816d9fd6004.addr2line.39b02397e671b2d1-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib(gimli-46dc78dc6a8cb06a.gimli.9d272e8433f81454-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib(rustc_demangle-146c3f1190dee2e2.rustc_demangle.c5a78273c295e539-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib(miniz_oxide-5ad929a15a8e6727.miniz_oxide.b662226d77c6ee8e-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib(adler2-1f570ee5c6635aae.adler2.1d6706876a417dbf-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib(alloc-6e6df4ffe0af4d15.alloc.fdfd2bd8633a6659-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib(core-120cbae4e86ec454.core.c1f1a4ba060b9bfa-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.132.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.187.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.201.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.261.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libm.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libmvec.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libc.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib64",
      "kind": "dynamic_library",
      "path": "/lib64/ld-linux-x86-64.so.2",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o",
      "source": "link_trace"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-711817-1783995938275708739.map",
  "pid": 711817,
  "ppid": 711723,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-711817-1783995938275708739.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 0,
  "parsed_event_count": 0,
  "phase": "start",
  "platform": "linux_ebpf",
  "raw_event_count": 0,
  "spawn_error": null,
  "stderr": "",
  "stdout": ""
}
```

#### Record 14

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 196,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 198,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "oe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n6.893   cc               711447 711446   0 \n6.893   cc               711571 710401   0 \n6.893   cat              711612 711606   0 \n6.893   sed              711646 711606   0 \n6.893   as               711419 707670   0 \n6.893   collect2         711448 711447   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKETOtt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n6.893   rustc            711599 710289   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tiny_xlib --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tiny-xlib-0.2.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --cfg feature=\"default\" --cfg feature=\"dlopen\" --cfg ...\n6.893   build-script-bu  711575 710289   0 \n6.894   sleep            711613 711606   0 \n6.894   cargo            711660 708144   0 \n6.895   collect2         711588 711580   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2YA6Dz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n6.895   sed              711607 711606   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n6.895   cat              711608 711606   0 /usr/bin/cat /proc/2240539/stat\n6.895   rust-lld         711589 711588   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2YA6Dz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0 ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2YA6Dz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n6.895   pkg-config       711591 711575   0 /tmp/native-trace-706714-1783995875047/shims/pkg-config --variable=libdir x11-xcb\n6.895   cpuUsage.sh      711606 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n6.895   riscv64-linux-g  711636 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n6.895   cat              711658 711606   0 \n7.369   rustc            711675 711660   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n7.406   rustc            711678 710289   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_scanner --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-scanner-0.31.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n7.425   runc             711683 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1280194222 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n7.507   exe              711693 711683   0 /proc/self/exe init\n7.531   curl             711695 711683   0 /usr/bin/curl -f http://localhost:9091/healthz\n7.806   cross            711719 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n7.810   rustc            711721 711719   0 /home/xmoe/.cargo/bin/rustc --print target-list\n7.900   rustc            711723 711660   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"neon-sys\")) -C metadata=eb8dc297def29e68 ...\n7.900   rustc            711721 711719   0 \n7.998   rustc            711758 711749   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n7.998   rustc            711739 711719   0 /home/xmoe/.cargo/bin/rustc -vV\n7.998   rustc            711739 711719   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n7.998   cargo            711749 711719   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n7.998   cargo            711749 711719   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n8.010   as               711764 708961   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n8.063   rustc            711760 711749   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.155   powerpc64le-lin  711762 629465   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n8.174   rustc            711773 711749   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n8.251   cc1plus          711774 711762   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/RemoveImports.cpp ...\n8.410   rustc            711779 711719   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n8.418   rustc            711779 711719   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n8.448   runc             711800 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1654370240 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n8.495   docker           711811 711719   0 \n8.496   exe              711809 711800   0 /proc/self/exe init\n8.497   cc               711817 711723   0 /tmp/native-trace-708144-1783995896528/shims/cc -m64 /target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n8.497   rustc            711810 700964   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(doc_cfg) --cfg feature=\"default\" --cfg ...\n8.497   cc               711820 711817   0 /usr/bin/cc -m64 /target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n8.506   rustc            711799 710289   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client_system\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"client_system\", \"dlopen\", \"log\", \"raw-window-handle\", \"rwh_06\", \"server_system\")) ...\n8.550   docker           711828 711719   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n8.579   collect2         711841 711820   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczDk5yc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n8.585   ld.lld           711842 711841   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczDk5yc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc ...\n8.588   rust-lld         711842 711841   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczDk5yc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n8.620   16               711844 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n8.642   frpc             711844 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n8.649   runc             711855 1599     0 /usr/bin/runc --version\n8.658   docker-init      711873 1599     0 /usr/bin/docker-init --version\n8.774   docker           711879 711719   0 /usr/bin/docker info -f {{.SecurityOptions}}\n8.834   etcdctl          711872 711800   0 /usr/local/bin/etcdctl endpoint health\n8.906   runc             711889 1599     0 /usr/bin/runc --version\n8.918   docker-init      711894 1599     0 \n8.937   build-script-bu  711896 711660   0 /target/debug/build/neon-build-e65906ab291905fc/build-script-build\n8.949   rustc            711898 711660   0 \n8.962   rustup           711902 711719   0 /home/xmoe/.local/bin/rustup toolchain list\n8.975   rustup           711912 711719   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n8.995   rustc            711913 701100   0 \n9.036   rustup           711925 711719   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n9.568   sh               711975 2147557   0 /bin/sh -c which ps\n9.632   riscv64-linux-g  711964 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n9.637   which            711975 2147557   0 /usr/bin/which ps\n9.662   cc1plus          711983 711964   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n9.739   sh               711990 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n9.740   ps               711990 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n10.041  cc               711993 711799   0 /tmp/native-trace-706714-1783995875047/shims/cc -m64 /target/debug/build/wayland-backend-b7dc8af064836d48/rustcdnjxnG/symbols.o /target/debug/build/wayland-backend-b7dc8af064836d48/build_script_build-b7dc8af064836d48.build_script_build.af0559c80409153f-cgu /target/debug/build/wayland-backend-b7dc8af064836d48/build_script_build-b7dc8af064836d48.3poilti6y5hd519526jhafc89.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-a82a821952bfd3a9.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n10.042  cc               711994 711993   0 /usr/bin/cc -m64 /target/debug/build/wayland-backend-b7dc8af064836d48/rustcdnjxnG/symbols.o /target/debug/build/wayland-backend-b7dc8af064836d48/build_script_build-b7dc8af064836d48.build_script_build.af0559c80409153f-cgu /target/debug/build/wayland-backend-b7dc8af064836d48/build_script_build-b7dc8af064836d48.3poilti6y5hd519526jhafc89.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-a82a821952bfd3a9.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n10.061  collect2         711995 711994   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOsJ0BP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n10.067  uname            711996 711719   0 /usr/bin/uname -r\n10.072  ld.lld           711998 711995   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOsJ0BP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/wayland-backend-b7dc8af064836d48/build_script_build-b7dc8af064836d48 ...\n10.083  rust-lld         711998 711995   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOsJ0BP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n10.117  docker           711999 711719   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n10.139  sh               712000 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n10.141  cpuUsage.sh      712000 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n10.143  sed              712001 712000   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n10.214  cat              712007 712000   0 /usr/bin/cat /proc/2240539/stat\n10.293  cat              712011 712000   0 /usr/bin/cat /proc/4193716/stat\n10.294  sleep            712012 712000   0 /usr/bin/sleep 1\n11.296  sed              712034 712000   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n11.473  cat              712042 712000   0 /usr/bin/cat /proc/2240539/stat\n11.556  cat              712046 712000   0 /usr/bin/cat /proc/4193716/stat\n11.615  systemd-sysctl   712048 712043   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfe71417 --prefix=/net/ipv4/neigh/vethfe71417 --prefix=/net/ipv6/conf/vethfe71417 --prefix=/net/ipv6/neigh/vethfe71417\n11.651  systemd-sysctl   712051 712044   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethee99610 --prefix=/net/ipv4/neigh/vethee99610 --prefix=/net/ipv6/conf/vethee99610 --prefix=/net/ipv6/neigh/vethee99610\n11.797  build-script-bu  712063 710289   0 /target/debug/build/wayland-backend-b7dc8af064836d48/build-script-build\n12.334  containerd-shim  712096 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a88991cc5 start\n12.477  rustc            712097 710289   0 \n12.477  rustc            712098 710289   0 \n12.477  containerd-shim  712116 712096   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a88991cc5 -address /var/run/docker/containerd/containerd.sock\n12.478  rustc            712107 708203   0 \n12.478  runc             712126 712116   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a889 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a889 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a889 2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a88991cc5\n12.796  exe              712143 712126   0 /proc/self/exe init\n13.049  rustc            712149 710289   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustix --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.36/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n13.435  exe              712170 712126   0 /proc/1599/exe -exec-root=/var/run/docker 2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a88991cc5 d7da31e8f8e1\n13.823  exe              712209 1599     0 /proc/self/exe /var/run/docker/netns/d30f4c43d1ef all false\n14.469  runc             712260 712116   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a889 --log-format json --systemd-cgroup start 2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a88991cc5\n14.477  sh               712151 712116   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n14.478  cargo            712266 712151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n14.660  sh               712281 2147557   0 \n14.660  which            712280 2147557   0 \n14.660  sh               712280 2147557   0 /bin/sh -c which ps\n14.700  cargo-native-tr  712266 712151   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n14.706  cargo            712288 712266   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n14.734  ps               712281 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command= /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.916  rustc            712294 712288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.104  cc               712300 711601   0 /tmp/native-trace-705346-1783995855869/shims/cc -Wl,--version-script=/target/debug/deps/rustcTL8THN/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTL8THN/symbols.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.09.rcgu.o /target/debug/deps/rustcTL8THN/rmeta.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.b9vd6vj40q477xi869v30t1f0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7fb6f22735bb8f35.rlib ...\n15.105  cc               712301 712300   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcTL8THN/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTL8THN/symbols.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.09.rcgu.o /target/debug/deps/rustcTL8THN/rmeta.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.b9vd6vj40q477xi869v30t1f0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7fb6f22735bb8f35.rlib ...\n15.110  collect2         712302 712301   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMKMTI1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTL8THN/raw-dylibs ...\n15.112  ld.lld           712303 712302   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMKMTI1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTL8THN/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.116  rust-lld         712303 712302   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMKMTI1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.348  rustc            712312 712288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.408  sh               712316 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n15.410  cpuUsage.sh      712316 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n15.412  sed              712317 712316   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.496  cat              712327 712316   0 /usr/bin/cat /proc/2240539/stat\n15.601  cat              712328 712316   0 /usr/bin/cat /proc/4193716/stat\n15.603  sleep            712345 712316   0 /usr/bin/sleep 1\n15.720  execsnoop        712351 712266   0 \n15.720  python3          712351 712266   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.068  cc               712370 711519   0 /tmp/native-trace-698664-1783995773347/shims/cc -m64 /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/rustcjiJMoc/symbols.o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.06pyughktk6cyp8rkkbdjqyjp.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.09cgye4evk6dluun2oarit4cr.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0f4zrfk4l3b2bg38ky2qdvgbo.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ggelndrflgppje1amhap113f.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ioi0mks4febnfni11jt6y060.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0iwonz5qk3jsdz4n10qhqwga3.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0otvfrx40z5ctvbn7cr0mpgqu.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0zkba66gem7x9d2wj4aunolwf.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.14ovywp9x2203e31jq7quvi9v.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1kso9bai48bir8jc7na7uy7px.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1ln6cvg6m23rqs008nui5ptvu.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1n43g60370h5rmq2u2jbunqa7.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.22jxanjuuu2ayf5dfeti7vrwf.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.23fg8c5j532e2pq21716avvr1.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.26cc9rws44xm76yd6c2cyt504.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.29786dvz4tm5gdtv84jhtk45d.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.2a6f46t1vpwxohk6jadgkfr1w.0wap2hc.rcg ...\n16.164  cc               712373 712370   0 /usr/bin/cc -m64 /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/rustcjiJMoc/symbols.o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.06pyughktk6cyp8rkkbdjqyjp.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.09cgye4evk6dluun2oarit4cr.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0f4zrfk4l3b2bg38ky2qdvgbo.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ggelndrflgppje1amhap113f.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ioi0mks4febnfni11jt6y060.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0iwonz5qk3jsdz4n10qhqwga3.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0otvfrx40z5ctvbn7cr0mpgqu.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0zkba66gem7x9d2wj4aunolwf.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.14ovywp9x2203e31jq7quvi9v.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1kso9bai48bir8jc7na7uy7px.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1ln6cvg6m23rqs008nui5ptvu.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1n43g60370h5rmq2u2jbunqa7.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.22jxanjuuu2ayf5dfeti7vrwf.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.23fg8c5j532e2pq21716avvr1.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.26cc9rws44xm76yd6c2cyt504.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.29786dvz4tm5gdtv84jhtk45d.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.2a6f46t1vpwxohk6jadgkfr1w.0wap2hc.rcg ...\n16.405  collect2         712374 712373   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdy1rjx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.577  ld.lld           712375 712374   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdy1rjx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0 ...\n16.705  sed              712378 712316   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.708  rust-lld         712375 712374   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdy1rjx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.893  cat              712381 712316   0 /usr/bin/cat /proc/2240539/stat\n17.051  cat              712387 712316   0 /usr/bin/cat /proc/4193716/stat\n19.096  runc             712477 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2942372893 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n19.202  rustc            712476 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytemuck --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck-1.18.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --deny=unexpected_cfgs --check-cfg cfg(target_arch, values(\"spirv\")) --cfg feature=\"bytemuck_derive\" --cfg ...\n19.238  exe              712497 712477   0 /proc/self/exe init\n19.554  sh               712558 2147557   0 /bin/sh -c which ps\n19.724  which            712558 2147557   0 /usr/bin/which ps\n19.744  sh               712565 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.746  ps               712565 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.844  curl             712499 712477   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n20.344  cc               712589 711678   0 /tmp/native-trace-706714-1783995875047/shims/cc -Wl,--version-script=/target/debug/deps/rustcTpxi0E/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTpxi0E/symbols.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.00.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.01.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.02.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.03.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.04.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.05.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.06.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.07.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.08.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.09.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.10.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.11.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.12.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.13.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.14.rcgu.o ...\n20.345  cc               712590 712589   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcTpxi0E/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTpxi0E/symbols.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.00.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.01.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.02.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.03.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.04.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.05.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.06.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.07.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.08.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.09.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.10.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.11.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.12.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.13.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.14.rcgu.o ...\n20.350  collect2         712591 712590   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cck01PyV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libwayland_scanner-7cf2fd5987c470ca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTpxi0E/raw-dylibs ...\n20.352  ld.lld           712592 712591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cck01PyV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libwayland_scanner-7cf2fd5987c470ca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTpxi0E/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.354  rust-lld         712592 712591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cck01PyV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libwayland_scanner-7cf2fd5987c470ca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.536  cc               712595 711810   0 /tmp/native-trace-698605-1783995772302/shims/cc -m64 /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/rustcC1dbsp/symbols.o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.06pyughktk6cyp8rkkbdjqyjp.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.09cgye4evk6dluun2oarit4cr.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0f4zrfk4l3b2bg38ky2qdvgbo.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ggelndrflgppje1amhap113f.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ioi0mks4febnfni11jt6y060.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0iwonz5qk3jsdz4n10qhqwga3.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0otvfrx40z5ctvbn7cr0mpgqu.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0zkba66gem7x9d2wj4aunolwf.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.14ovywp9x2203e31jq7quvi9v.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1kso9bai48bir8jc7na7uy7px.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1ln6cvg6m23rqs008nui5ptvu.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1n43g60370h5rmq2u2jbunqa7.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.22jxanjuuu2ayf5dfeti7vrwf.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.23fg8c5j532e2pq21716avvr1.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.26cc9rws44xm76yd6c2cyt504.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.29786dvz4tm5gdtv84jhtk45d.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.2a6f46t1vpwxohk6jadgkfr1w.1qioeqe.rcg ...\n20.668  sh               712593 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n20.669  cpuUsage.sh      712593 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n20.669  cc               712596 712595   0 \n20.736  sed              712598 712593   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.770  collect2         712600 712596   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU0TVHi.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.865  cat              712602 712593   0 \n20.865  ld.lld           712601 712600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU0TVHi.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0 ...\n20.921  rust-lld         712601 712600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU0TVHi.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.944  cat              712603 712593   0 /usr/bin/cat /proc/4193716/stat\n20.947  sleep            712604 712593   0 /usr/bin/sleep 1\n21.205  build-script-bu  712626 699965   0 /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build-script-build\n21.275  curl             712627 712626   0 /tmp/native-trace-697761-1783995762509/shims/curl -sSL -o /target/aarch64-unknown-linux-gnu/debug/build/utoipa-swagger-ui-d432d77fd257fb49/out/v5.17.14.zip https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n21.376  cc               712631 712630   0 \n21.376  cc               712630 712107   0 /tmp/native-trace-705371-1783995855832/shims/cc -Wl,--version-script=/target/debug/deps/rustcGGcCUK/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcGGcCUK/symbols.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.09.rcgu.o /target/debug/deps/rustcGGcCUK/rmeta.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.b9vd6vj40q477xi869v30t1f0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7fb6f22735bb8f35.rlib ...\n21.378  collect2         712632 712631   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfhUhKP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcGGcCUK/raw-dylibs ...\n21.383  ld.lld           712634 712632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfhUhKP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcGGcCUK/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.385  rust-lld         712634 712632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfhUhKP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n21.427  curl             712629 712627   0 /usr/bin/curl -sSL -o /target/aarch64-unknown-linux-gnu/debug/build/utoipa-swagger-ui-d432d77fd257fb49/out/v5.17.14.zip https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n21.454  as               712638 630007   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/f05a870cbfed04a9-wasm-s-parser.o /tmp/cc1EOW2m.s\n22.028  sed              712660 712593   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n22.116  cat              712662 712593   0 /usr/bin/cat /proc/2240539/stat\n22.234  cat              712664 712593   0 /usr/bin/cat /proc/4193716/stat\n22.811  as               712675 666250   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/bd3f41d09f19c9b0-StackIR.o /tmp/ccYkoCxS.s\n24.220  rustc            712709 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_backend --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client_system\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"client_system\", \"dlopen\", \"log\", \"raw-window-handle\", \"rwh_06\", \"server_system\")) ...\n24.222  rustc            712713 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11rb --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-0.13.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"allow-unsafe-code\" --cfg feature=\"as-raw-xcb-connection\" --cfg feature=\"dl-libxcb\" ...\n24.228  rustc            712714 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name drm_ffi --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-ffi-0.8.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"use_bindgen\")) -C metadata=ad97500dc5c734ed ...\n24.350  rustc            712715 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytemuck --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck-1.18.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --deny=unexpected_cfgs --check-cfg cfg(target_arch, values(\"spirv\")) --cfg feature=\"bytemuck_derive\" --cfg ...\n24.620  16               712721 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n24.635  frpc             712721 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n24.676  curl             712729 712627   0 /usr/bin/curl -L --fail --silent --show-error -o /tmp/native-trace-redownload-712627-1783995954456469161.tmp https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n25.641  rustc            712752 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name drm_ffi --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-ffi-0.8.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"use_bindgen\")) -C metadata=cae742aa8d2077d0 ...\n25.645  rustc            712753 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_backend --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client_system\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"client_system\", \"dlopen\", \"log\", \"raw-window-handle\", \"rwh_06\", \"server_system\")) ...\n25.968  rustc            712755 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11rb --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-0.13.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"allow-unsafe-code\" --cfg feature=\"as-raw-xcb-connection\" --cfg feature=\"dl-libxcb\" ...\n26.753  as               712786 659328   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/f7deeeb1a9f9c241-module-utils.o /tmp/cclUZXZv.s\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/neon-build-e65906ab291905fc/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 711896,
  "build_script_target_dir": "neon-build-e65906ab291905fc",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/neon-build-e65906ab291905fc/build-script-build",
  "pid": 711896,
  "ppid": 711660,
  "root_cargo_pid": 711660,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "_build_script_out_dir": "/target/debug/build/neon-build-e65906ab291905fc/out"
}
```

#### Record 16

```json
{
  "crate": "neon-build",
  "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "event_id": "bsrun:c8dd7b813bc1b300:5d901863a1ab6152:d609610d7fb63399",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/neon-build-e65906ab291905fc/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
  "out_dir": "/target/debug/build/neon-build-e65906ab291905fc/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
  "success": true,
  "target": null,
  "version": "0.10.1",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:25:58.897600+00:00",
  "crate": "neon-build",
  "version": "0.10.1",
  "architecture": "riscv64",
  "duration_seconds": 77.47308505838737,
  "trace_record_count": 16,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "manifest_path": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1/Cargo.toml"
      }
    ],
    "attributed_event_count": 13,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "neon-build",
        "version": "0.10.1",
        "event_count": 13,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 7,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "workspace_root": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
          "name": "neon-build",
          "version": "0.10.1",
          "manifest_path": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1"
        }
      ],
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 711817,
      "ppid": 711723,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "neon-build",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "event_id": "used:cc:b26a5b85a6b58e60:dc81ad933d976d1c:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
      "pid": 711817,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "neon-build",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "event_id": "used:cc:b26a5b85a6b58e60:b69cfa0a6e6d3c6c:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
      "pid": 711817,
      "sha256": "b7cdeae91144abfd6a0bd45b657951c6c3e044b0479fc430a1ba50a77b7e7c55",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "neon-build",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "event_id": "used:cc:b26a5b85a6b58e60:6ea06483502cce10:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
      "pid": 711817,
      "sha256": "8a81f72dac85d8e5b0c8fc2053085e6fa6a451277aac149ff022c9db10b9f0a2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "neon-build",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "event_id": "used:cc:b26a5b85a6b58e60:87ae85677c1f9134:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
      "pid": 711817,
      "sha256": "cb5789a05a4b4d36485425edfde577b1d9c5df9f0cce5d6f6baba9241e5b9471",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "neon-build",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "event_id": "used:cc:b26a5b85a6b58e60:d8181a265005ddd0:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
      "pid": 711817,
      "sha256": "552e84852629177a0e560729a243fa32c1cc010e8b8e42892681b94af3f6868d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "neon-build",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "event_id": "used:cc:b26a5b85a6b58e60:39c241499cfe5df5:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
      "pid": 711817,
      "sha256": "0a2646bbca76ca6f51cdc49d83372ae7ebf0b03bf03d3c47654b7aa892ef1c73",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "neon-build",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "event_id": "used:cc:b26a5b85a6b58e60:5bf41dc1ee611c52:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
      "pid": 711817,
      "sha256": "7f5f25f66313cb930aa311987364b0fea55f1fc6c5bf1d12a673e82c9d3d3a5d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib"
      ],
      "libs": [
        "gcc_s",
        "util",
        "rt",
        "pthread",
        "m",
        "dl",
        "c"
      ],
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "cargo_pkg_name": "neon-build",
      "cargo_pkg_version": "0.10.1",
      "context_path": "/tmp/native-trace-708144-1783995896528/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-708144-1783995896528/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 711817,
      "ppid": 711723,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC",
        "/target/debug/build/neon-build-e65906ab291905fc",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu",
        "/lib64"
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib(std-d1237ef7159db0a2.std.e28293b1aa0f68bd-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib(panic_unwind-4be5972b22d3a6da.panic_unwind.d9b2f7d287d2f9d2-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib(object-2a81194c9d07bbf6.object.4f4cc23e276cbdd5-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib(memchr-ea71fa85f6699d6b.memchr.9642f0ce76a98c65-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib(addr2line-a79a8816d9fd6004.addr2line.39b02397e671b2d1-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib(gimli-46dc78dc6a8cb06a.gimli.9d272e8433f81454-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib(rustc_demangle-146c3f1190dee2e2.rustc_demangle.c5a78273c295e539-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib(miniz_oxide-5ad929a15a8e6727.miniz_oxide.b662226d77c6ee8e-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib(adler2-1f570ee5c6635aae.adler2.1d6706876a417dbf-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib(alloc-6e6df4ffe0af4d15.alloc.fdfd2bd8633a6659-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib(core-120cbae4e86ec454.core.c1f1a4ba060b9bfa-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.132.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.187.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.201.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.261.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libm.so.6",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libmvec.so.1",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libc.so.6",
          "source": "link_trace"
        },
        {
          "directory": "/lib64",
          "kind": "dynamic_library",
          "path": "/lib64/ld-linux-x86-64.so.2",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o",
          "source": "link_trace"
        }
      ],
      "kind": "resolved_link",
      "map_path": "/tmp/native-trace-link-cc-711817-1783995938275708739.map",
      "pid": 711817,
      "ppid": 711723,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-711817-1783995938275708739.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "/usr/local/bin/execsnoop",
        "-t"
      ],
      "event": "process_tracer_diagnostic",
      "exit_status": null,
      "parse_error_count": 0,
      "parsed_event_count": 0,
      "phase": "start",
      "platform": "linux_ebpf",
      "raw_event_count": 0,
      "spawn_error": null,
      "stderr": "",
      "stdout": ""
    },
    {
      "argv": [
        "/usr/local/bin/execsnoop",
        "-t"
      ],
      "event": "process_tracer_diagnostic",
      "exit_status": null,
      "parse_error_count": 2,
      "parsed_event_count": 196,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 198,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "oe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n6.893   cc               711447 711446   0 \n6.893   cc               711571 710401   0 \n6.893   cat              711612 711606   0 \n6.893   sed              711646 711606   0 \n6.893   as               711419 707670   0 \n6.893   collect2         711448 711447   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKETOtt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n6.893   rustc            711599 710289   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tiny_xlib --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tiny-xlib-0.2.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --cfg feature=\"default\" --cfg feature=\"dlopen\" --cfg ...\n6.893   build-script-bu  711575 710289   0 \n6.894   sleep            711613 711606   0 \n6.894   cargo            711660 708144   0 \n6.895   collect2         711588 711580   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2YA6Dz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n6.895   sed              711607 711606   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n6.895   cat              711608 711606   0 /usr/bin/cat /proc/2240539/stat\n6.895   rust-lld         711589 711588   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2YA6Dz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0 ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2YA6Dz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n6.895   pkg-config       711591 711575   0 /tmp/native-trace-706714-1783995875047/shims/pkg-config --variable=libdir x11-xcb\n6.895   cpuUsage.sh      711606 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n6.895   riscv64-linux-g  711636 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n6.895   cat              711658 711606   0 \n7.369   rustc            711675 711660   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n7.406   rustc            711678 710289   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_scanner --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-scanner-0.31.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n7.425   runc             711683 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1280194222 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n7.507   exe              711693 711683   0 /proc/self/exe init\n7.531   curl             711695 711683   0 /usr/bin/curl -f http://localhost:9091/healthz\n7.806   cross            711719 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n7.810   rustc            711721 711719   0 /home/xmoe/.cargo/bin/rustc --print target-list\n7.900   rustc            711723 711660   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"neon-sys\")) -C metadata=eb8dc297def29e68 ...\n7.900   rustc            711721 711719   0 \n7.998   rustc            711758 711749   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n7.998   rustc            711739 711719   0 /home/xmoe/.cargo/bin/rustc -vV\n7.998   rustc            711739 711719   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n7.998   cargo            711749 711719   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n7.998   cargo            711749 711719   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n8.010   as               711764 708961   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n8.063   rustc            711760 711749   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.155   powerpc64le-lin  711762 629465   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n8.174   rustc            711773 711749   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n8.251   cc1plus          711774 711762   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/RemoveImports.cpp ...\n8.410   rustc            711779 711719   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n8.418   rustc            711779 711719   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n8.448   runc             711800 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1654370240 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n8.495   docker           711811 711719   0 \n8.496   exe              711809 711800   0 /proc/self/exe init\n8.497   cc               711817 711723   0 /tmp/native-trace-708144-1783995896528/shims/cc -m64 /target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n8.497   rustc            711810 700964   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(doc_cfg) --cfg feature=\"default\" --cfg ...\n8.497   cc               711820 711817   0 /usr/bin/cc -m64 /target/debug/build/neon-build-e65906ab291905fc/rustcydXXBC/symbols.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.01rjqnp.rcgu.o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.01rjqnp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n8.506   rustc            711799 710289   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client_system\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"client_system\", \"dlopen\", \"log\", \"raw-window-handle\", \"rwh_06\", \"server_system\")) ...\n8.550   docker           711828 711719   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n8.579   collect2         711841 711820   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczDk5yc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n8.585   ld.lld           711842 711841   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczDk5yc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc ...\n8.588   rust-lld         711842 711841   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczDk5yc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n8.620   16               711844 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n8.642   frpc             711844 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n8.649   runc             711855 1599     0 /usr/bin/runc --version\n8.658   docker-init      711873 1599     0 /usr/bin/docker-init --version\n8.774   docker           711879 711719   0 /usr/bin/docker info -f {{.SecurityOptions}}\n8.834   etcdctl          711872 711800   0 /usr/local/bin/etcdctl endpoint health\n8.906   runc             711889 1599     0 /usr/bin/runc --version\n8.918   docker-init      711894 1599     0 \n8.937   build-script-bu  711896 711660   0 /target/debug/build/neon-build-e65906ab291905fc/build-script-build\n8.949   rustc            711898 711660   0 \n8.962   rustup           711902 711719   0 /home/xmoe/.local/bin/rustup toolchain list\n8.975   rustup           711912 711719   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n8.995   rustc            711913 701100   0 \n9.036   rustup           711925 711719   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n9.568   sh               711975 2147557   0 /bin/sh -c which ps\n9.632   riscv64-linux-g  711964 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n9.637   which            711975 2147557   0 /usr/bin/which ps\n9.662   cc1plus          711983 711964   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n9.739   sh               711990 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n9.740   ps               711990 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n10.041  cc               711993 711799   0 /tmp/native-trace-706714-1783995875047/shims/cc -m64 /target/debug/build/wayland-backend-b7dc8af064836d48/rustcdnjxnG/symbols.o /target/debug/build/wayland-backend-b7dc8af064836d48/build_script_build-b7dc8af064836d48.build_script_build.af0559c80409153f-cgu /target/debug/build/wayland-backend-b7dc8af064836d48/build_script_build-b7dc8af064836d48.3poilti6y5hd519526jhafc89.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-a82a821952bfd3a9.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n10.042  cc               711994 711993   0 /usr/bin/cc -m64 /target/debug/build/wayland-backend-b7dc8af064836d48/rustcdnjxnG/symbols.o /target/debug/build/wayland-backend-b7dc8af064836d48/build_script_build-b7dc8af064836d48.build_script_build.af0559c80409153f-cgu /target/debug/build/wayland-backend-b7dc8af064836d48/build_script_build-b7dc8af064836d48.3poilti6y5hd519526jhafc89.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-a82a821952bfd3a9.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n10.061  collect2         711995 711994   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOsJ0BP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n10.067  uname            711996 711719   0 /usr/bin/uname -r\n10.072  ld.lld           711998 711995   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOsJ0BP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/wayland-backend-b7dc8af064836d48/build_script_build-b7dc8af064836d48 ...\n10.083  rust-lld         711998 711995   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOsJ0BP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n10.117  docker           711999 711719   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n10.139  sh               712000 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n10.141  cpuUsage.sh      712000 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n10.143  sed              712001 712000   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n10.214  cat              712007 712000   0 /usr/bin/cat /proc/2240539/stat\n10.293  cat              712011 712000   0 /usr/bin/cat /proc/4193716/stat\n10.294  sleep            712012 712000   0 /usr/bin/sleep 1\n11.296  sed              712034 712000   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n11.473  cat              712042 712000   0 /usr/bin/cat /proc/2240539/stat\n11.556  cat              712046 712000   0 /usr/bin/cat /proc/4193716/stat\n11.615  systemd-sysctl   712048 712043   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfe71417 --prefix=/net/ipv4/neigh/vethfe71417 --prefix=/net/ipv6/conf/vethfe71417 --prefix=/net/ipv6/neigh/vethfe71417\n11.651  systemd-sysctl   712051 712044   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethee99610 --prefix=/net/ipv4/neigh/vethee99610 --prefix=/net/ipv6/conf/vethee99610 --prefix=/net/ipv6/neigh/vethee99610\n11.797  build-script-bu  712063 710289   0 /target/debug/build/wayland-backend-b7dc8af064836d48/build-script-build\n12.334  containerd-shim  712096 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a88991cc5 start\n12.477  rustc            712097 710289   0 \n12.477  rustc            712098 710289   0 \n12.477  containerd-shim  712116 712096   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a88991cc5 -address /var/run/docker/containerd/containerd.sock\n12.478  rustc            712107 708203   0 \n12.478  runc             712126 712116   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a889 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a889 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a889 2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a88991cc5\n12.796  exe              712143 712126   0 /proc/self/exe init\n13.049  rustc            712149 710289   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustix --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.36/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n13.435  exe              712170 712126   0 /proc/1599/exe -exec-root=/var/run/docker 2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a88991cc5 d7da31e8f8e1\n13.823  exe              712209 1599     0 /proc/self/exe /var/run/docker/netns/d30f4c43d1ef all false\n14.469  runc             712260 712116   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a889 --log-format json --systemd-cgroup start 2603cfd266c1a84c832fc52708181257c8ebc438ea9a60fcce33ce2a88991cc5\n14.477  sh               712151 712116   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n14.478  cargo            712266 712151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n14.660  sh               712281 2147557   0 \n14.660  which            712280 2147557   0 \n14.660  sh               712280 2147557   0 /bin/sh -c which ps\n14.700  cargo-native-tr  712266 712151   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n14.706  cargo            712288 712266   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n14.734  ps               712281 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command= /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.916  rustc            712294 712288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.104  cc               712300 711601   0 /tmp/native-trace-705346-1783995855869/shims/cc -Wl,--version-script=/target/debug/deps/rustcTL8THN/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTL8THN/symbols.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.09.rcgu.o /target/debug/deps/rustcTL8THN/rmeta.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.b9vd6vj40q477xi869v30t1f0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7fb6f22735bb8f35.rlib ...\n15.105  cc               712301 712300   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcTL8THN/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTL8THN/symbols.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.09.rcgu.o /target/debug/deps/rustcTL8THN/rmeta.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.b9vd6vj40q477xi869v30t1f0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7fb6f22735bb8f35.rlib ...\n15.110  collect2         712302 712301   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMKMTI1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTL8THN/raw-dylibs ...\n15.112  ld.lld           712303 712302   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMKMTI1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTL8THN/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.116  rust-lld         712303 712302   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMKMTI1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.348  rustc            712312 712288   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.408  sh               712316 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n15.410  cpuUsage.sh      712316 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n15.412  sed              712317 712316   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.496  cat              712327 712316   0 /usr/bin/cat /proc/2240539/stat\n15.601  cat              712328 712316   0 /usr/bin/cat /proc/4193716/stat\n15.603  sleep            712345 712316   0 /usr/bin/sleep 1\n15.720  execsnoop        712351 712266   0 \n15.720  python3          712351 712266   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.068  cc               712370 711519   0 /tmp/native-trace-698664-1783995773347/shims/cc -m64 /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/rustcjiJMoc/symbols.o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.06pyughktk6cyp8rkkbdjqyjp.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.09cgye4evk6dluun2oarit4cr.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0f4zrfk4l3b2bg38ky2qdvgbo.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ggelndrflgppje1amhap113f.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ioi0mks4febnfni11jt6y060.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0iwonz5qk3jsdz4n10qhqwga3.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0otvfrx40z5ctvbn7cr0mpgqu.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0zkba66gem7x9d2wj4aunolwf.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.14ovywp9x2203e31jq7quvi9v.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1kso9bai48bir8jc7na7uy7px.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1ln6cvg6m23rqs008nui5ptvu.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1n43g60370h5rmq2u2jbunqa7.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.22jxanjuuu2ayf5dfeti7vrwf.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.23fg8c5j532e2pq21716avvr1.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.26cc9rws44xm76yd6c2cyt504.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.29786dvz4tm5gdtv84jhtk45d.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.2a6f46t1vpwxohk6jadgkfr1w.0wap2hc.rcg ...\n16.164  cc               712373 712370   0 /usr/bin/cc -m64 /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/rustcjiJMoc/symbols.o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.06pyughktk6cyp8rkkbdjqyjp.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.09cgye4evk6dluun2oarit4cr.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0f4zrfk4l3b2bg38ky2qdvgbo.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ggelndrflgppje1amhap113f.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ioi0mks4febnfni11jt6y060.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0iwonz5qk3jsdz4n10qhqwga3.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0otvfrx40z5ctvbn7cr0mpgqu.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0zkba66gem7x9d2wj4aunolwf.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.14ovywp9x2203e31jq7quvi9v.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1kso9bai48bir8jc7na7uy7px.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1ln6cvg6m23rqs008nui5ptvu.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1n43g60370h5rmq2u2jbunqa7.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.22jxanjuuu2ayf5dfeti7vrwf.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.23fg8c5j532e2pq21716avvr1.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.26cc9rws44xm76yd6c2cyt504.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.29786dvz4tm5gdtv84jhtk45d.0wap2hc.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.2a6f46t1vpwxohk6jadgkfr1w.0wap2hc.rcg ...\n16.405  collect2         712374 712373   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdy1rjx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.577  ld.lld           712375 712374   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdy1rjx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0 ...\n16.705  sed              712378 712316   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.708  rust-lld         712375 712374   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdy1rjx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.893  cat              712381 712316   0 /usr/bin/cat /proc/2240539/stat\n17.051  cat              712387 712316   0 /usr/bin/cat /proc/4193716/stat\n19.096  runc             712477 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2942372893 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n19.202  rustc            712476 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytemuck --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck-1.18.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --deny=unexpected_cfgs --check-cfg cfg(target_arch, values(\"spirv\")) --cfg feature=\"bytemuck_derive\" --cfg ...\n19.238  exe              712497 712477   0 /proc/self/exe init\n19.554  sh               712558 2147557   0 /bin/sh -c which ps\n19.724  which            712558 2147557   0 /usr/bin/which ps\n19.744  sh               712565 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.746  ps               712565 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.844  curl             712499 712477   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n20.344  cc               712589 711678   0 /tmp/native-trace-706714-1783995875047/shims/cc -Wl,--version-script=/target/debug/deps/rustcTpxi0E/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTpxi0E/symbols.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.00.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.01.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.02.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.03.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.04.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.05.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.06.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.07.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.08.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.09.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.10.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.11.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.12.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.13.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.14.rcgu.o ...\n20.345  cc               712590 712589   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcTpxi0E/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTpxi0E/symbols.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.00.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.01.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.02.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.03.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.04.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.05.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.06.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.07.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.08.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.09.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.10.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.11.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.12.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.13.rcgu.o /target/debug/deps/wayland_scanner-7cf2fd5987c470ca.wayland_scanner.559f76f195e081e4-cgu.14.rcgu.o ...\n20.350  collect2         712591 712590   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cck01PyV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libwayland_scanner-7cf2fd5987c470ca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTpxi0E/raw-dylibs ...\n20.352  ld.lld           712592 712591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cck01PyV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libwayland_scanner-7cf2fd5987c470ca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTpxi0E/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.354  rust-lld         712592 712591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cck01PyV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libwayland_scanner-7cf2fd5987c470ca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.536  cc               712595 711810   0 /tmp/native-trace-698605-1783995772302/shims/cc -m64 /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/rustcC1dbsp/symbols.o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.06pyughktk6cyp8rkkbdjqyjp.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.09cgye4evk6dluun2oarit4cr.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0f4zrfk4l3b2bg38ky2qdvgbo.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ggelndrflgppje1amhap113f.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0ioi0mks4febnfni11jt6y060.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0iwonz5qk3jsdz4n10qhqwga3.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0otvfrx40z5ctvbn7cr0mpgqu.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.0zkba66gem7x9d2wj4aunolwf.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.14ovywp9x2203e31jq7quvi9v.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1kso9bai48bir8jc7na7uy7px.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1ln6cvg6m23rqs008nui5ptvu.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.1n43g60370h5rmq2u2jbunqa7.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.22jxanjuuu2ayf5dfeti7vrwf.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.23fg8c5j532e2pq21716avvr1.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.26cc9rws44xm76yd6c2cyt504.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.29786dvz4tm5gdtv84jhtk45d.1qioeqe.rcg /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0.2a6f46t1vpwxohk6jadgkfr1w.1qioeqe.rcg ...\n20.668  sh               712593 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n20.669  cpuUsage.sh      712593 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n20.669  cc               712596 712595   0 \n20.736  sed              712598 712593   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.770  collect2         712600 712596   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU0TVHi.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.865  cat              712602 712593   0 \n20.865  ld.lld           712601 712600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU0TVHi.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build_script_build-bfef17a127b0d9b0 ...\n20.921  rust-lld         712601 712600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU0TVHi.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.944  cat              712603 712593   0 /usr/bin/cat /proc/4193716/stat\n20.947  sleep            712604 712593   0 /usr/bin/sleep 1\n21.205  build-script-bu  712626 699965   0 /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build-script-build\n21.275  curl             712627 712626   0 /tmp/native-trace-697761-1783995762509/shims/curl -sSL -o /target/aarch64-unknown-linux-gnu/debug/build/utoipa-swagger-ui-d432d77fd257fb49/out/v5.17.14.zip https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n21.376  cc               712631 712630   0 \n21.376  cc               712630 712107   0 /tmp/native-trace-705371-1783995855832/shims/cc -Wl,--version-script=/target/debug/deps/rustcGGcCUK/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcGGcCUK/symbols.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.09.rcgu.o /target/debug/deps/rustcGGcCUK/rmeta.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.b9vd6vj40q477xi869v30t1f0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7fb6f22735bb8f35.rlib ...\n21.378  collect2         712632 712631   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfhUhKP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcGGcCUK/raw-dylibs ...\n21.383  ld.lld           712634 712632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfhUhKP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcGGcCUK/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.385  rust-lld         712634 712632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfhUhKP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n21.427  curl             712629 712627   0 /usr/bin/curl -sSL -o /target/aarch64-unknown-linux-gnu/debug/build/utoipa-swagger-ui-d432d77fd257fb49/out/v5.17.14.zip https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n21.454  as               712638 630007   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/f05a870cbfed04a9-wasm-s-parser.o /tmp/cc1EOW2m.s\n22.028  sed              712660 712593   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n22.116  cat              712662 712593   0 /usr/bin/cat /proc/2240539/stat\n22.234  cat              712664 712593   0 /usr/bin/cat /proc/4193716/stat\n22.811  as               712675 666250   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/bd3f41d09f19c9b0-StackIR.o /tmp/ccYkoCxS.s\n24.220  rustc            712709 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_backend --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client_system\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"client_system\", \"dlopen\", \"log\", \"raw-window-handle\", \"rwh_06\", \"server_system\")) ...\n24.222  rustc            712713 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11rb --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-0.13.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"allow-unsafe-code\" --cfg feature=\"as-raw-xcb-connection\" --cfg feature=\"dl-libxcb\" ...\n24.228  rustc            712714 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name drm_ffi --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-ffi-0.8.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"use_bindgen\")) -C metadata=ad97500dc5c734ed ...\n24.350  rustc            712715 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytemuck --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck-1.18.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --deny=unexpected_cfgs --check-cfg cfg(target_arch, values(\"spirv\")) --cfg feature=\"bytemuck_derive\" --cfg ...\n24.620  16               712721 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n24.635  frpc             712721 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n24.676  curl             712729 712627   0 /usr/bin/curl -L --fail --silent --show-error -o /tmp/native-trace-redownload-712627-1783995954456469161.tmp https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n25.641  rustc            712752 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name drm_ffi --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-ffi-0.8.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"use_bindgen\")) -C metadata=cae742aa8d2077d0 ...\n25.645  rustc            712753 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_backend --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client_system\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"client_system\", \"dlopen\", \"log\", \"raw-window-handle\", \"rwh_06\", \"server_system\")) ...\n25.968  rustc            712755 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11rb --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-0.13.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"allow-unsafe-code\" --cfg feature=\"as-raw-xcb-connection\" --cfg feature=\"dl-libxcb\" ...\n26.753  as               712786 659328   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/f7deeeb1a9f9c241-module-utils.o /tmp/cclUZXZv.s\n"
    },
    {
      "argv": [
        "/target/debug/build/neon-build-e65906ab291905fc/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 711896,
      "build_script_target_dir": "neon-build-e65906ab291905fc",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/neon-build-e65906ab291905fc/build-script-build",
      "pid": 711896,
      "ppid": 711660,
      "root_cargo_pid": 711660,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "neon-build",
      "cwd": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "event_id": "bsrun:c8dd7b813bc1b300:5d901863a1ab6152:d609610d7fb63399",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/neon-build-e65906ab291905fc/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
      "out_dir": "/target/debug/build/neon-build-e65906ab291905fc/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
      "success": true,
      "target": null,
      "version": "0.10.1",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-riscv64-xn1rmh7c/src/neon-build-0.10.1",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 2603,
    "crate": "neon-build",
    "version": "0.10.1",
    "crate_id": "8150",
    "version_id": "554039",
    "downloads": 4673425,
    "cumulative_downloads": 105217892705,
    "cumulative_share_of_global": 0.39338541066160404,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "build.rs",
    "build_script_exists": true,
    "package_build_field": "build.rs",
    "build_script_reason": "package_build_path",
    "download_source": "local"
  }
}
```
