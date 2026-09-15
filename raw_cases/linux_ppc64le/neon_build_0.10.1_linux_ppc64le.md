# `neon-build` `0.10.1`

Platform: Linux ppc64le

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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2",
    "/target/debug/build/neon-build-e65906ab291905fc",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu"
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so",
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
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libc.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o",
      "source": "link_trace"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-712862-1783995958239355504.map",
  "pid": 712862,
  "ppid": 712829,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-712862-1783995958239355504.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "workspace_root": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
      "name": "neon-build",
      "version": "0.10.1",
      "manifest_path": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1"
    }
  ],
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 712862,
  "ppid": 712829,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "event_id": "used:cc:26c55559cc4cdbd7:b22070f33ca1c679:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
  "pid": 712862,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "event_id": "used:cc:26c55559cc4cdbd7:53078fcf3f2f61d5:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
  "pid": 712862,
  "sha256": "e8a8e009052706e6e8ed5a35d819b09a4ca18e64297c18b7bd763818ed73082c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "event_id": "used:cc:26c55559cc4cdbd7:ac0bbab3d7c9a952:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
  "pid": 712862,
  "sha256": "cd7dc216b1d067d6034d957d229d6ec5df0d3b106f23fe1bc267e93dfbc469d3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "event_id": "used:cc:26c55559cc4cdbd7:545669f6d4cef6be:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
  "pid": 712862,
  "sha256": "b9bc3743197d8eb4be93ef6cf526362a3f2d66e98c57e888f015957cae08dcdc",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "event_id": "used:cc:26c55559cc4cdbd7:49fc88094eecd5f7:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
  "pid": 712862,
  "sha256": "0ef8bc7e223b20bfb06f39d9e1ac328dc8b640d8ae5c19c91bb3bce1b628ec8f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "event_id": "used:cc:26c55559cc4cdbd7:dfdd6c5333ea3e47:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
  "pid": 712862,
  "sha256": "69ad604ba0349e0ea16ff7f7bd7d9c765ab335d02467a11f1ba5b020e1482b60",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "event_id": "used:cc:26c55559cc4cdbd7:137bdfc58cf264d2:cce90896fe54c8da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
  "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
  "pid": 712862,
  "sha256": "7f5f25f66313cb930aa311987364b0fea55f1fc6c5bf1d12a673e82c9d3d3a5d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "cargo_pkg_name": "neon-build",
  "cargo_pkg_version": "0.10.1",
  "context_path": "/tmp/native-trace-710448-1783995922603/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-710448-1783995922603/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 712862,
  "ppid": 712829,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
    "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2",
    "/target/debug/build/neon-build-e65906ab291905fc",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu"
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/neon-build-e65906ab291905fc",
      "kind": "object",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so",
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
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libc.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o",
      "source": "link_trace"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-712862-1783995958239355504.map",
  "pid": 712862,
  "ppid": 712829,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-712862-1783995958239355504.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
  "parsed_event_count": 245,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 247,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": " /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n9.211   cc1plus          713053 713050   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/param-utils.cpp ...\n9.404   riscv64-linux-g  713103 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n9.411   cc1plus          713110 713103   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n9.639   cc               713149 712946   0 /tmp/native-trace-710545-1783995924131/shims/cc -m64 /target/debug/build/libc-9c45a53025127314/rustcTKGEjX/symbols.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.0.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.1.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.2.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.8larzxiuzjdfb8lf0bknoot0j.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n9.641   cc               713150 713149   0 /usr/bin/cc -m64 /target/debug/build/libc-9c45a53025127314/rustcTKGEjX/symbols.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.0.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.1.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.2.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.8larzxiuzjdfb8lf0bknoot0j.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n9.646   collect2         713151 713150   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQlE7tf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.702   sh               713154 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n9.702   ps               713154 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n9.702   ld.lld           713153 713151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQlE7tf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314 ...\n9.702   rust-lld         713153 713151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQlE7tf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.702   sh               713152 2147557   0 /bin/sh -c which ps\n9.702   which            713152 2147557   0 /usr/bin/which ps\n10.332  rustc            713163 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_client --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-client-0.31.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"log\")) -C metadata=37f4ee68e3801922 ...\n10.517  cc               713164 712802   0 /tmp/native-trace-706714-1783995875047/shims/cc -Wl,--version-script=/target/debug/deps/rustcWHPRBs/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcWHPRBs/symbols.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.09.rcgu.o /target/debug/deps/rustcWHPRBs/rmeta.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.b9vd6vj40q477xi869v30t1f0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7fb6f22735bb8f35.rlib ...\n10.563  cc               713184 713164   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcWHPRBs/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcWHPRBs/symbols.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.09.rcgu.o /target/debug/deps/rustcWHPRBs/rmeta.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.b9vd6vj40q477xi869v30t1f0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7fb6f22735bb8f35.rlib ...\n10.594  curl             713186 713028   0 /usr/bin/curl -L --fail --silent --show-error -o /tmp/native-trace-redownload-713028-1783995963451882680.tmp https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n10.624  collect2         713188 713184   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOTKHrN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcWHPRBs/raw-dylibs ...\n10.628  ld.lld           713189 713188   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOTKHrN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcWHPRBs/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n10.630  rust-lld         713189 713188   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOTKHrN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n10.707  sh               713191 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n10.709  cpuUsage.sh      713191 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n10.711  sed              713192 713191   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n10.714  cat              713193 713191   0 /usr/bin/cat /proc/2240539/stat\n10.783  cat              713194 713191   0 /usr/bin/cat /proc/4193716/stat\n10.785  sleep            713196 713191   0 /usr/bin/sleep 1\n10.803  cross            713197 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n10.836  rustc            713201 713197   0 /home/xmoe/.cargo/bin/rustc --print target-list\n11.080  build-script-bu  713221 712908   0 /target/debug/build/libc-9c45a53025127314/build-script-build\n11.084  rustc            713222 713221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.103  rustc            713201 713197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n11.201  rustc            713241 712908   0 \n11.211  rustc            713243 713197   0 /home/xmoe/.cargo/bin/rustc -vV\n11.224  rustc            713243 713197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.298  cargo            713264 713197   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n11.488  rustc            713275 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_client --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-client-0.31.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"log\")) -C metadata=ff4599aee35b6545 ...\n11.497  cargo            713264 713197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n11.855  sed              713292 713191   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n11.859  cat              713293 713191   0 /usr/bin/cat /proc/2240539/stat\n11.862  cat              713295 713191   0 /usr/bin/cat /proc/4193716/stat\n11.882  build-script-bu  713298 700964   0 /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build-script-build\n11.899  curl             713299 713298   0 /tmp/native-trace-698605-1783995772302/shims/curl -sSL -o /target/riscv64gc-unknown-linux-gnu/debug/build/utoipa-swagger-ui-0b3b559aeba211eb/out/v5.17.14.zip https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n11.902  curl             713300 713299   0 /usr/bin/curl -sSL -o /target/riscv64gc-unknown-linux-gnu/debug/build/utoipa-swagger-ui-0b3b559aeba211eb/out/v5.17.14.zip https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n11.903  rustc            713301 713264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.920  rustc            713304 713264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n11.952  rustc            713308 713264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n12.003  rustc            713313 713197   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n12.011  rustc            713313 713197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n12.038  docker           713328 713197   0 /usr/bin/docker --help\n12.057  aarch64-linux-g  713329 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n12.062  cc1plus          713335 713329   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/MemoryPacking.cpp ...\n12.074  rustc            713327 710289   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytemuck --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck-1.18.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --deny=unexpected_cfgs --check-cfg cfg(target_arch, values(\"spirv\")) --cfg feature=\"bytemuck_derive\" --cfg ...\n12.400  docker           713348 713197   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n12.719  runc             713360 1599     0 /usr/bin/runc --version\n12.857  docker-init      713366 1599     0 /usr/bin/docker-init --version\n12.942  docker           713369 713197   0 /usr/bin/docker info -f {{.SecurityOptions}}\n13.234  runc             713382 1599     0 /usr/bin/runc --version\n13.366  riscv64-linux-g  713392 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n13.477  cc1plus          713394 713392   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n13.504  docker-init      713396 1599     0 /usr/bin/docker-init \n13.819  curl             713399 713299   0 /usr/bin/curl -L --fail --silent --show-error -o /tmp/native-trace-redownload-713299-1783995966675948294.tmp https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n14.137  as               713406 708766   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n14.178  rustup           713407 713197   0 \n14.194  rustup           713417 713197   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n14.273  rustc            713429 712908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rlimit --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=fc6e46b90c8cb4c8 ...\n14.307  rustup           713433 713197   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n14.436  uname            713443 713197   0 /usr/bin/uname -r\n14.468  docker           713444 713197   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n14.685  sh               713461 2147557   0 /bin/sh -c which ps\n14.688  which            713461 2147557   0 /usr/bin/which ps\n14.691  sh               713462 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.693  ps               713462 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.782  sh               713464 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n14.784  cpuUsage.sh      713464 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n14.787  sed              713465 713464   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.791  cat              713466 713464   0 /usr/bin/cat /proc/2240539/stat\n14.793  cat              713467 713464   0 /usr/bin/cat /proc/4193716/stat\n14.795  sleep            713468 713464   0 /usr/bin/sleep 1\n15.020  runc             713474 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process3996559064 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n15.056  exe              713481 713474   0 /proc/self/exe init\n15.183  as               713487 711762   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/bd3f41d09f19c9b0-RemoveImports.o /tmp/ccoWnCWk.s\n15.262  runc             713497 697605   0 \n15.327  as               713522 709547   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-OptimizeForJS.o /tmp/ccYjDhlM.s\n15.426  curl             713490 713474   0 /usr/bin/curl -f http://localhost:9091/healthz\n15.474  systemd-sysctl   713531 713529   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha9a3b8b --prefix=/net/ipv4/neigh/vetha9a3b8b --prefix=/net/ipv6/conf/vetha9a3b8b --prefix=/net/ipv6/neigh/vetha9a3b8b\n15.507  systemd-sysctl   713532 713530   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha9aff0b --prefix=/net/ipv4/neigh/vetha9aff0b --prefix=/net/ipv6/conf/vetha9aff0b --prefix=/net/ipv6/neigh/vetha9aff0b\n15.531  runc             713528 697605   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeee --log-format json --systemd-cgroup delete eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeeed7e23\n15.606  riscv64-linux-g  713557 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n15.612  cc1plus          713559 713557   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n15.713  cc1plus          713575 713574   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/RemoveUnusedNames.cpp ...\n15.714  powerpc64le-lin  713574 629465   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n15.814  cat              713594 713464   0 /usr/bin/cat /proc/2240539/stat\n15.814  cat              713601 713464   0 /usr/bin/cat /proc/4193716/stat\n15.814  sed              713593 713464   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.821  containerd-shim  713589 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2ee6cc8 start\n15.830  containerd-shim  713615 713589   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2ee6cc8 -address /var/run/docker/containerd/containerd.sock\n15.882  as               713638 708152   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/bd3f41d09f19c9b0-StackCheck.o /tmp/ccFHyMuj.s\n15.885  containerd-shim  713639 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeeed7e23 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeee delete\n15.893  runc             713647 713639   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeeed7e2 --log-format json delete --force eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeeed7e23\n15.904  runc             713649 713615   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2e 47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2ee6cc8\n15.970  exe              713659 713649   0 /proc/self/exe init\n16.312  systemd-sysctl   713675 713529   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth336b13c --prefix=/net/ipv4/neigh/veth336b13c --prefix=/net/ipv6/conf/veth336b13c --prefix=/net/ipv6/neigh/veth336b13c\n16.323  exe              713677 713649   0 /proc/1599/exe -exec-root=/var/run/docker 47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2ee6cc8 d7da31e8f8e1\n17.040  16               713693 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n17.163  frpc             713693 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.742  runc             713707 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process4052579621 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n17.970  aarch64-linux-g  713714 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n18.005  exe              713717 713707   0 /proc/self/exe init\n18.051  cc1plus          713726 713714   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n18.074  etcdctl          713719 713707   0 /usr/local/bin/etcdctl endpoint health\n18.263  exe              713733 1599     0 /proc/self/exe /var/run/docker/netns/a65c995ceb99 all false\n18.277  as               713739 706829   0 \n18.389  runc             713747 713615   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2e --log-format json --systemd-cgroup start 47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2ee6cc8\n18.410  sh               713668 713615   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.412  cargo            713753 713668   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n18.437  cargo-native-tr  713753 713668   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n18.484  rustc            713760 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name softbuffer --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"as-raw-xcb-connection\" --cfg feature=\"bytemuck\" --cfg feature=\"default\" ...\n18.564  as               713765 700889   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-RedundantSetElimination.o /tmp/ccU8KC07.s\n18.602  cargo            713758 713753   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.688  rustc            713768 713758   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.703  rustc            713771 713758   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.733  execsnoop        713776 713753   0 /usr/local/bin/execsnoop -t\n18.737  python3          713776 713753   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.760  as               713780 665835   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n18.792  rustc            713782 700964   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name utoipa_swagger_ui --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(doc_cfg) --cfg feature=\"default\" --cfg ...\n19.785  rustc            713792 701100   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name utoipa_swagger_ui --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(doc_cfg) --cfg feature=\"default\" --cfg ...\n19.794  sh               713794 2147557   0 /bin/sh -c which ps\n19.797  which            713794 2147557   0 /usr/bin/which ps\n19.802  sh               713795 2147557   0 \n19.807  ps               713795 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command= /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.830  rustc            713798 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name softbuffer --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"as-raw-xcb-connection\" --cfg feature=\"bytemuck\" --cfg feature=\"default\" ...\n20.099  as               713803 705141   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-Precompute.o /tmp/ccwjw9oE.s\n20.125  cargo            713805 712266   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n20.201  rustc            713806 713805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.402  rustc            713813 713805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.427  rustc            713814 713805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=f456834a0050c6c4 ...\n20.611  sh               713816 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n20.674  cpuUsage.sh      713816 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n20.736  sed              713817 713816   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.765  aarch64-linux-g  713822 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n20.830  cat              713823 713816   0 \n20.830  cat              713824 713816   0 \n20.830  sleep            713825 713816   0 /usr/bin/sleep 1\n20.860  cc1plus          713829 713822   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/ReorderFunctions.cpp ...\n21.528  cc               713846 713814   0 /tmp/native-trace-712266-1783995944481/shims/cc -m64 /target/debug/build/rlimit-b1973589b3158e11/rustcSPZKmr/symbols.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.0lu6kvcvyltaog4mhmj5k1xr9.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.17uevghcqpa1yg8iw5yw6wgay.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.1ke1eu5kih7j0t4piz5yx97un.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.2u8elygoxrsy7iwn54ar5y3w2.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.37mxjrz9ofqa2n18emlwj9c21.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.adfty1nehusgeb7gw3ru3mu97.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.bqlfwd0oll1rcrmp9valukd9l.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.bz96fe4ggs5rsqrva74zkdxzi.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.c1zj8zs7o0p7v7y9kqubfaz9w.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.cjg1i8fd8ufsdnx4u81skufxl.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.cwoidtqv765hpyuyb9oslsg23.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.d56uie2v83bp4z556v7p25h0l.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.9u2civmsw4xr9nh8upqouel3t.0m501bv.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n21.589  cc               713847 713846   0 /usr/bin/cc -m64 /target/debug/build/rlimit-b1973589b3158e11/rustcSPZKmr/symbols.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.0lu6kvcvyltaog4mhmj5k1xr9.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.17uevghcqpa1yg8iw5yw6wgay.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.1ke1eu5kih7j0t4piz5yx97un.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.2u8elygoxrsy7iwn54ar5y3w2.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.37mxjrz9ofqa2n18emlwj9c21.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.adfty1nehusgeb7gw3ru3mu97.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.bqlfwd0oll1rcrmp9valukd9l.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.bz96fe4ggs5rsqrva74zkdxzi.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.c1zj8zs7o0p7v7y9kqubfaz9w.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.cjg1i8fd8ufsdnx4u81skufxl.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.cwoidtqv765hpyuyb9oslsg23.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.d56uie2v83bp4z556v7p25h0l.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.9u2civmsw4xr9nh8upqouel3t.0m501bv.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n21.627  collect2         713848 713847   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfEpFq5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.629  ld.lld           713849 713848   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfEpFq5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11 ...\n21.631  rust-lld         713849 713848   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfEpFq5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.924  sed              713856 713816   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n22.008  cat              713857 713816   0 /usr/bin/cat /proc/2240539/stat\n22.088  cat              713859 713816   0 /usr/bin/cat /proc/4193716/stat\n22.716  powerpc64le-lin  713879 626080   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I ...\n22.778  build-script-bu  713881 713805   0 /target/debug/build/rlimit-b1973589b3158e11/build-script-build\n22.820  cc1plus          713882 713879   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n23.270  cc               713884 713813   0 /tmp/native-trace-712266-1783995944481/shims/cc -m64 /target/debug/build/libc-9c45a53025127314/rustc8POnvs/symbols.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.0.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.1.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.2.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.8larzxiuzjdfb8lf0bknoot0j.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n23.272  cc               713885 713884   0 /usr/bin/cc -m64 /target/debug/build/libc-9c45a53025127314/rustc8POnvs/symbols.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.0.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.1.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.2.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.8larzxiuzjdfb8lf0bknoot0j.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n23.275  collect2         713886 713885   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsEtSkh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n23.277  ld.lld           713887 713886   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsEtSkh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314 ...\n23.281  rust-lld         713887 713886   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsEtSkh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n23.391  build-script-bu  713913 713805   0 /target/debug/build/libc-9c45a53025127314/build-script-build\n23.396  rustc            713914 713913   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n23.434  rustc            713936 713805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n23.489  aarch64-linux-g  713941 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n23.498  cc1plus          713942 713941   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n24.131  systemd-userwor  713992 50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n24.131  systemd-userwor  713993 50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n24.530  cross            714022 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n24.530  rustc            714025 714022   0 /home/xmoe/.cargo/bin/rustc --print target-list\n24.531  as               714026 626065   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/f05a870cbfed04a9-wasm-s-parser.o /tmp/cce4EHrj.s\n24.540  rustc            714025 714022   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n24.600  rustc            714040 714022   0 /home/xmoe/.cargo/bin/rustc -vV\n24.609  rustc            714040 714022   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n24.871  cargo            714053 714022   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n24.915  sh               714050 2147557   0 /bin/sh -c which ps\n24.917  which            714050 2147557   0 /usr/bin/which ps\n24.917  riscv64-linux-g  714054 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n24.919  sh               714055 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n25.015  ps               714055 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n25.106  cc1plus          714056 714054   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n25.195  cargo            714053 714022   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n25.544  rustc            714079 714053   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n25.618  sh               714090 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n25.619  cpuUsage.sh      714090 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n25.623  sed              714091 714090   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n25.627  cat              714092 714090   0 /usr/bin/cat /proc/2240539/stat\n25.629  cat              714093 714090   0 /usr/bin/cat /proc/4193716/stat\n25.711  sleep            714095 714090   0 /usr/bin/sleep 1\n25.787  rustc            714101 714053   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n25.969  rustc            714114 714053   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/neon-build-e65906ab291905fc/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 712906,
  "build_script_target_dir": "neon-build-e65906ab291905fc",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/neon-build-e65906ab291905fc/build-script-build",
  "pid": 712906,
  "ppid": 712800,
  "root_cargo_pid": 712800,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "_build_script_out_dir": "/target/debug/build/neon-build-e65906ab291905fc/out"
}
```

#### Record 16

```json
{
  "crate": "neon-build",
  "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "event_id": "bsrun:d6878b0e0fc0d5e0:5d901863a1ab6152:d609610d7fb63399",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/neon-build-e65906ab291905fc/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
  "out_dir": "/target/debug/build/neon-build-e65906ab291905fc/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
  "success": true,
  "target": null,
  "version": "0.10.1",
  "_owner": {
    "crate": "neon-build",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:26:21.417061+00:00",
  "crate": "neon-build",
  "version": "0.10.1",
  "architecture": "ppc64le",
  "duration_seconds": 73.26594734424725,
  "trace_record_count": 16,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "manifest_path": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "workspace_root": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
          "name": "neon-build",
          "version": "0.10.1",
          "manifest_path": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1"
        }
      ],
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 712862,
      "ppid": 712829,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "event_id": "used:cc:26c55559cc4cdbd7:b22070f33ca1c679:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
      "pid": 712862,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "event_id": "used:cc:26c55559cc4cdbd7:53078fcf3f2f61d5:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
      "pid": 712862,
      "sha256": "e8a8e009052706e6e8ed5a35d819b09a4ca18e64297c18b7bd763818ed73082c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "event_id": "used:cc:26c55559cc4cdbd7:ac0bbab3d7c9a952:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
      "pid": 712862,
      "sha256": "cd7dc216b1d067d6034d957d229d6ec5df0d3b106f23fe1bc267e93dfbc469d3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "event_id": "used:cc:26c55559cc4cdbd7:545669f6d4cef6be:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
      "pid": 712862,
      "sha256": "b9bc3743197d8eb4be93ef6cf526362a3f2d66e98c57e888f015957cae08dcdc",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "event_id": "used:cc:26c55559cc4cdbd7:49fc88094eecd5f7:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
      "pid": 712862,
      "sha256": "0ef8bc7e223b20bfb06f39d9e1ac328dc8b640d8ae5c19c91bb3bce1b628ec8f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "event_id": "used:cc:26c55559cc4cdbd7:dfdd6c5333ea3e47:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
      "pid": 712862,
      "sha256": "69ad604ba0349e0ea16ff7f7bd7d9c765ab335d02467a11f1ba5b020e1482b60",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "event_id": "used:cc:26c55559cc4cdbd7:137bdfc58cf264d2:cce90896fe54c8da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc",
      "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
      "pid": 712862,
      "sha256": "7f5f25f66313cb930aa311987364b0fea55f1fc6c5bf1d12a673e82c9d3d3a5d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "cargo_pkg_name": "neon-build",
      "cargo_pkg_version": "0.10.1",
      "context_path": "/tmp/native-trace-710448-1783995922603/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-710448-1783995922603/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 712862,
      "ppid": 712829,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
        "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2",
        "/target/debug/build/neon-build-e65906ab291905fc",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu"
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/rustcwbxSf2/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.0so9gao96hzgxjghs63it0l2r.1rrb5bp.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.6z6bkdzplsjwc6y9ishgncmns.1rrb5bp.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.91s56hny75wm1dc1yl37zikn6.1rrb5bp.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.9c8ep7k47tb6eon1yk179myp2.1rrb5bp.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.eyv3m7jg34rdv4v4njagca0nf.1rrb5bp.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/neon-build-e65906ab291905fc",
          "kind": "object",
          "path": "/target/debug/build/neon-build-e65906ab291905fc/build_script_build-e65906ab291905fc.ew3ke9uncqf4jyus6rm2zvx0c.1rrb5bp.rcgu.o",
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
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so",
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
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libc.so.6",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o",
          "source": "link_trace"
        }
      ],
      "kind": "resolved_link",
      "map_path": "/tmp/native-trace-link-cc-712862-1783995958239355504.map",
      "pid": 712862,
      "ppid": 712829,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-712862-1783995958239355504.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
      "parsed_event_count": 245,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 247,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": " /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n9.211   cc1plus          713053 713050   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/param-utils.cpp ...\n9.404   riscv64-linux-g  713103 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n9.411   cc1plus          713110 713103   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n9.639   cc               713149 712946   0 /tmp/native-trace-710545-1783995924131/shims/cc -m64 /target/debug/build/libc-9c45a53025127314/rustcTKGEjX/symbols.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.0.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.1.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.2.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.8larzxiuzjdfb8lf0bknoot0j.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n9.641   cc               713150 713149   0 /usr/bin/cc -m64 /target/debug/build/libc-9c45a53025127314/rustcTKGEjX/symbols.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.0.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.1.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.2.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.8larzxiuzjdfb8lf0bknoot0j.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n9.646   collect2         713151 713150   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQlE7tf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.702   sh               713154 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n9.702   ps               713154 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n9.702   ld.lld           713153 713151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQlE7tf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314 ...\n9.702   rust-lld         713153 713151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQlE7tf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.702   sh               713152 2147557   0 /bin/sh -c which ps\n9.702   which            713152 2147557   0 /usr/bin/which ps\n10.332  rustc            713163 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_client --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-client-0.31.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"log\")) -C metadata=37f4ee68e3801922 ...\n10.517  cc               713164 712802   0 /tmp/native-trace-706714-1783995875047/shims/cc -Wl,--version-script=/target/debug/deps/rustcWHPRBs/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcWHPRBs/symbols.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.09.rcgu.o /target/debug/deps/rustcWHPRBs/rmeta.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.b9vd6vj40q477xi869v30t1f0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7fb6f22735bb8f35.rlib ...\n10.563  cc               713184 713164   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcWHPRBs/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcWHPRBs/symbols.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.bytemuck_derive.8f4e5dbb58d14f21-cgu.09.rcgu.o /target/debug/deps/rustcWHPRBs/rmeta.o /target/debug/deps/bytemuck_derive-56e95e6a94b0b4e5.b9vd6vj40q477xi869v30t1f0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7fb6f22735bb8f35.rlib ...\n10.594  curl             713186 713028   0 /usr/bin/curl -L --fail --silent --show-error -o /tmp/native-trace-redownload-713028-1783995963451882680.tmp https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n10.624  collect2         713188 713184   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOTKHrN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcWHPRBs/raw-dylibs ...\n10.628  ld.lld           713189 713188   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOTKHrN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcWHPRBs/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n10.630  rust-lld         713189 713188   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOTKHrN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-56e95e6a94b0b4e5.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n10.707  sh               713191 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n10.709  cpuUsage.sh      713191 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n10.711  sed              713192 713191   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n10.714  cat              713193 713191   0 /usr/bin/cat /proc/2240539/stat\n10.783  cat              713194 713191   0 /usr/bin/cat /proc/4193716/stat\n10.785  sleep            713196 713191   0 /usr/bin/sleep 1\n10.803  cross            713197 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n10.836  rustc            713201 713197   0 /home/xmoe/.cargo/bin/rustc --print target-list\n11.080  build-script-bu  713221 712908   0 /target/debug/build/libc-9c45a53025127314/build-script-build\n11.084  rustc            713222 713221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.103  rustc            713201 713197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n11.201  rustc            713241 712908   0 \n11.211  rustc            713243 713197   0 /home/xmoe/.cargo/bin/rustc -vV\n11.224  rustc            713243 713197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.298  cargo            713264 713197   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n11.488  rustc            713275 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_client --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-client-0.31.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"log\")) -C metadata=ff4599aee35b6545 ...\n11.497  cargo            713264 713197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n11.855  sed              713292 713191   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n11.859  cat              713293 713191   0 /usr/bin/cat /proc/2240539/stat\n11.862  cat              713295 713191   0 /usr/bin/cat /proc/4193716/stat\n11.882  build-script-bu  713298 700964   0 /target/debug/build/utoipa-swagger-ui-bfef17a127b0d9b0/build-script-build\n11.899  curl             713299 713298   0 /tmp/native-trace-698605-1783995772302/shims/curl -sSL -o /target/riscv64gc-unknown-linux-gnu/debug/build/utoipa-swagger-ui-0b3b559aeba211eb/out/v5.17.14.zip https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n11.902  curl             713300 713299   0 /usr/bin/curl -sSL -o /target/riscv64gc-unknown-linux-gnu/debug/build/utoipa-swagger-ui-0b3b559aeba211eb/out/v5.17.14.zip https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n11.903  rustc            713301 713264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.920  rustc            713304 713264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n11.952  rustc            713308 713264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n12.003  rustc            713313 713197   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n12.011  rustc            713313 713197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n12.038  docker           713328 713197   0 /usr/bin/docker --help\n12.057  aarch64-linux-g  713329 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n12.062  cc1plus          713335 713329   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/MemoryPacking.cpp ...\n12.074  rustc            713327 710289   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytemuck --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck-1.18.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --deny=unexpected_cfgs --check-cfg cfg(target_arch, values(\"spirv\")) --cfg feature=\"bytemuck_derive\" --cfg ...\n12.400  docker           713348 713197   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n12.719  runc             713360 1599     0 /usr/bin/runc --version\n12.857  docker-init      713366 1599     0 /usr/bin/docker-init --version\n12.942  docker           713369 713197   0 /usr/bin/docker info -f {{.SecurityOptions}}\n13.234  runc             713382 1599     0 /usr/bin/runc --version\n13.366  riscv64-linux-g  713392 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n13.477  cc1plus          713394 713392   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n13.504  docker-init      713396 1599     0 /usr/bin/docker-init \n13.819  curl             713399 713299   0 /usr/bin/curl -L --fail --silent --show-error -o /tmp/native-trace-redownload-713299-1783995966675948294.tmp https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip\n14.137  as               713406 708766   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n14.178  rustup           713407 713197   0 \n14.194  rustup           713417 713197   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n14.273  rustc            713429 712908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rlimit --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=fc6e46b90c8cb4c8 ...\n14.307  rustup           713433 713197   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n14.436  uname            713443 713197   0 /usr/bin/uname -r\n14.468  docker           713444 713197   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n14.685  sh               713461 2147557   0 /bin/sh -c which ps\n14.688  which            713461 2147557   0 /usr/bin/which ps\n14.691  sh               713462 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.693  ps               713462 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.782  sh               713464 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n14.784  cpuUsage.sh      713464 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n14.787  sed              713465 713464   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.791  cat              713466 713464   0 /usr/bin/cat /proc/2240539/stat\n14.793  cat              713467 713464   0 /usr/bin/cat /proc/4193716/stat\n14.795  sleep            713468 713464   0 /usr/bin/sleep 1\n15.020  runc             713474 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process3996559064 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n15.056  exe              713481 713474   0 /proc/self/exe init\n15.183  as               713487 711762   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/bd3f41d09f19c9b0-RemoveImports.o /tmp/ccoWnCWk.s\n15.262  runc             713497 697605   0 \n15.327  as               713522 709547   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-OptimizeForJS.o /tmp/ccYjDhlM.s\n15.426  curl             713490 713474   0 /usr/bin/curl -f http://localhost:9091/healthz\n15.474  systemd-sysctl   713531 713529   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha9a3b8b --prefix=/net/ipv4/neigh/vetha9a3b8b --prefix=/net/ipv6/conf/vetha9a3b8b --prefix=/net/ipv6/neigh/vetha9a3b8b\n15.507  systemd-sysctl   713532 713530   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha9aff0b --prefix=/net/ipv4/neigh/vetha9aff0b --prefix=/net/ipv6/conf/vetha9aff0b --prefix=/net/ipv6/neigh/vetha9aff0b\n15.531  runc             713528 697605   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeee --log-format json --systemd-cgroup delete eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeeed7e23\n15.606  riscv64-linux-g  713557 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n15.612  cc1plus          713559 713557   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n15.713  cc1plus          713575 713574   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/RemoveUnusedNames.cpp ...\n15.714  powerpc64le-lin  713574 629465   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n15.814  cat              713594 713464   0 /usr/bin/cat /proc/2240539/stat\n15.814  cat              713601 713464   0 /usr/bin/cat /proc/4193716/stat\n15.814  sed              713593 713464   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.821  containerd-shim  713589 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2ee6cc8 start\n15.830  containerd-shim  713615 713589   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2ee6cc8 -address /var/run/docker/containerd/containerd.sock\n15.882  as               713638 708152   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/bd3f41d09f19c9b0-StackCheck.o /tmp/ccFHyMuj.s\n15.885  containerd-shim  713639 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeeed7e23 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeee delete\n15.893  runc             713647 713639   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeeed7e2 --log-format json delete --force eafa5f42848eee599e095c19c42aa115ec48ed228c6bde99dbd3e20aeeed7e23\n15.904  runc             713649 713615   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2e 47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2ee6cc8\n15.970  exe              713659 713649   0 /proc/self/exe init\n16.312  systemd-sysctl   713675 713529   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth336b13c --prefix=/net/ipv4/neigh/veth336b13c --prefix=/net/ipv6/conf/veth336b13c --prefix=/net/ipv6/neigh/veth336b13c\n16.323  exe              713677 713649   0 /proc/1599/exe -exec-root=/var/run/docker 47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2ee6cc8 d7da31e8f8e1\n17.040  16               713693 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n17.163  frpc             713693 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.742  runc             713707 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process4052579621 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n17.970  aarch64-linux-g  713714 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n18.005  exe              713717 713707   0 /proc/self/exe init\n18.051  cc1plus          713726 713714   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n18.074  etcdctl          713719 713707   0 /usr/local/bin/etcdctl endpoint health\n18.263  exe              713733 1599     0 /proc/self/exe /var/run/docker/netns/a65c995ceb99 all false\n18.277  as               713739 706829   0 \n18.389  runc             713747 713615   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2e --log-format json --systemd-cgroup start 47f3e661f5673999c0c153bc3e67b9ed65325f7bef72e698f9a79faaa2ee6cc8\n18.410  sh               713668 713615   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.412  cargo            713753 713668   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n18.437  cargo-native-tr  713753 713668   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n18.484  rustc            713760 707813   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name softbuffer --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"as-raw-xcb-connection\" --cfg feature=\"bytemuck\" --cfg feature=\"default\" ...\n18.564  as               713765 700889   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-RedundantSetElimination.o /tmp/ccU8KC07.s\n18.602  cargo            713758 713753   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.688  rustc            713768 713758   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.703  rustc            713771 713758   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.733  execsnoop        713776 713753   0 /usr/local/bin/execsnoop -t\n18.737  python3          713776 713753   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.760  as               713780 665835   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n18.792  rustc            713782 700964   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name utoipa_swagger_ui --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(doc_cfg) --cfg feature=\"default\" --cfg ...\n19.785  rustc            713792 701100   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name utoipa_swagger_ui --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(doc_cfg) --cfg feature=\"default\" --cfg ...\n19.794  sh               713794 2147557   0 /bin/sh -c which ps\n19.797  which            713794 2147557   0 /usr/bin/which ps\n19.802  sh               713795 2147557   0 \n19.807  ps               713795 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command= /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.830  rustc            713798 708203   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name softbuffer --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"as-raw-xcb-connection\" --cfg feature=\"bytemuck\" --cfg feature=\"default\" ...\n20.099  as               713803 705141   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/bd3f41d09f19c9b0-Precompute.o /tmp/ccwjw9oE.s\n20.125  cargo            713805 712266   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n20.201  rustc            713806 713805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.402  rustc            713813 713805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.427  rustc            713814 713805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=f456834a0050c6c4 ...\n20.611  sh               713816 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n20.674  cpuUsage.sh      713816 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n20.736  sed              713817 713816   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.765  aarch64-linux-g  713822 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n20.830  cat              713823 713816   0 \n20.830  cat              713824 713816   0 \n20.830  sleep            713825 713816   0 /usr/bin/sleep 1\n20.860  cc1plus          713829 713822   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/ReorderFunctions.cpp ...\n21.528  cc               713846 713814   0 /tmp/native-trace-712266-1783995944481/shims/cc -m64 /target/debug/build/rlimit-b1973589b3158e11/rustcSPZKmr/symbols.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.0lu6kvcvyltaog4mhmj5k1xr9.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.17uevghcqpa1yg8iw5yw6wgay.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.1ke1eu5kih7j0t4piz5yx97un.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.2u8elygoxrsy7iwn54ar5y3w2.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.37mxjrz9ofqa2n18emlwj9c21.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.adfty1nehusgeb7gw3ru3mu97.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.bqlfwd0oll1rcrmp9valukd9l.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.bz96fe4ggs5rsqrva74zkdxzi.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.c1zj8zs7o0p7v7y9kqubfaz9w.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.cjg1i8fd8ufsdnx4u81skufxl.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.cwoidtqv765hpyuyb9oslsg23.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.d56uie2v83bp4z556v7p25h0l.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.9u2civmsw4xr9nh8upqouel3t.0m501bv.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n21.589  cc               713847 713846   0 /usr/bin/cc -m64 /target/debug/build/rlimit-b1973589b3158e11/rustcSPZKmr/symbols.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.0lu6kvcvyltaog4mhmj5k1xr9.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.17uevghcqpa1yg8iw5yw6wgay.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.1ke1eu5kih7j0t4piz5yx97un.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.2u8elygoxrsy7iwn54ar5y3w2.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.37mxjrz9ofqa2n18emlwj9c21.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.adfty1nehusgeb7gw3ru3mu97.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.bqlfwd0oll1rcrmp9valukd9l.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.bz96fe4ggs5rsqrva74zkdxzi.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.c1zj8zs7o0p7v7y9kqubfaz9w.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.cjg1i8fd8ufsdnx4u81skufxl.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.cwoidtqv765hpyuyb9oslsg23.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.d56uie2v83bp4z556v7p25h0l.0m501bv.rcgu.o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11.9u2civmsw4xr9nh8upqouel3t.0m501bv.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n21.627  collect2         713848 713847   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfEpFq5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.629  ld.lld           713849 713848   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfEpFq5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rlimit-b1973589b3158e11/build_script_build-b1973589b3158e11 ...\n21.631  rust-lld         713849 713848   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfEpFq5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.924  sed              713856 713816   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n22.008  cat              713857 713816   0 /usr/bin/cat /proc/2240539/stat\n22.088  cat              713859 713816   0 /usr/bin/cat /proc/4193716/stat\n22.716  powerpc64le-lin  713879 626080   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I ...\n22.778  build-script-bu  713881 713805   0 /target/debug/build/rlimit-b1973589b3158e11/build-script-build\n22.820  cc1plus          713882 713879   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n23.270  cc               713884 713813   0 /tmp/native-trace-712266-1783995944481/shims/cc -m64 /target/debug/build/libc-9c45a53025127314/rustc8POnvs/symbols.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.0.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.1.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.2.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.8larzxiuzjdfb8lf0bknoot0j.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n23.272  cc               713885 713884   0 /usr/bin/cc -m64 /target/debug/build/libc-9c45a53025127314/rustc8POnvs/symbols.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.0.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.1.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.build_script_build.426bdf463a239ff8-cgu.2.rcgu.o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314.8larzxiuzjdfb8lf0bknoot0j.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n23.275  collect2         713886 713885   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsEtSkh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n23.277  ld.lld           713887 713886   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsEtSkh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-9c45a53025127314/build_script_build-9c45a53025127314 ...\n23.281  rust-lld         713887 713886   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsEtSkh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n23.391  build-script-bu  713913 713805   0 /target/debug/build/libc-9c45a53025127314/build-script-build\n23.396  rustc            713914 713913   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n23.434  rustc            713936 713805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n23.489  aarch64-linux-g  713941 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n23.498  cc1plus          713942 713941   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n24.131  systemd-userwor  713992 50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n24.131  systemd-userwor  713993 50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n24.530  cross            714022 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n24.530  rustc            714025 714022   0 /home/xmoe/.cargo/bin/rustc --print target-list\n24.531  as               714026 626065   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/f05a870cbfed04a9-wasm-s-parser.o /tmp/cce4EHrj.s\n24.540  rustc            714025 714022   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n24.600  rustc            714040 714022   0 /home/xmoe/.cargo/bin/rustc -vV\n24.609  rustc            714040 714022   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n24.871  cargo            714053 714022   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n24.915  sh               714050 2147557   0 /bin/sh -c which ps\n24.917  which            714050 2147557   0 /usr/bin/which ps\n24.917  riscv64-linux-g  714054 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n24.919  sh               714055 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n25.015  ps               714055 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n25.106  cc1plus          714056 714054   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n25.195  cargo            714053 714022   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n25.544  rustc            714079 714053   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n25.618  sh               714090 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n25.619  cpuUsage.sh      714090 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n25.623  sed              714091 714090   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n25.627  cat              714092 714090   0 /usr/bin/cat /proc/2240539/stat\n25.629  cat              714093 714090   0 /usr/bin/cat /proc/4193716/stat\n25.711  sleep            714095 714090   0 /usr/bin/sleep 1\n25.787  rustc            714101 714053   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n25.969  rustc            714114 714053   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n"
    },
    {
      "argv": [
        "/target/debug/build/neon-build-e65906ab291905fc/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 712906,
      "build_script_target_dir": "neon-build-e65906ab291905fc",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/neon-build-e65906ab291905fc/build-script-build",
      "pid": 712906,
      "ppid": 712800,
      "root_cargo_pid": 712800,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "neon-build",
      "cwd": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "event_id": "bsrun:d6878b0e0fc0d5e0:5d901863a1ab6152:d609610d7fb63399",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/neon-build-e65906ab291905fc/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
      "out_dir": "/target/debug/build/neon-build-e65906ab291905fc/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
      "success": true,
      "target": null,
      "version": "0.10.1",
      "_owner": {
        "crate": "neon-build",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1#neon-build@0.10.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-oy8nk05d/src/neon-build-0.10.1",
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
