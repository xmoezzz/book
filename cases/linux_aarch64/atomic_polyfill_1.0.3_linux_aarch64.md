# `atomic-polyfill` `1.0.3`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 411724

Build-script executable: `/target/debug/build/atomic-polyfill-6f5883b967109919/build_script_build-6f5883b967109919`

Working directory: `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN4core3ptr106drop_in_place$LT$core..result..Result$LT$std..net..socket_addr..SocketAddr$C$std..io..error..Error$GT$$GT$17h25a3723fb0e0a46eE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.gcc_except_table._ZN4core3ptr106drop_in_place$LT$core..result..Result$LT$std..net..socket_addr..SocketAddr$C$std..io..error..Error$GT$$GT$17h25a3723fb0e0a46eE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN4core3ptr165drop_in_place$LT$core..iter..adapters..map..Map$LT$std..sys_common..net..LookupHost$C$std..net..socket_addr..resolve_socket_addr..$u7b$$u7b$closure$u7d$$u7d$$GT$$GT$17h9a2c926ea34033b6E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN4core3ptr77drop_in_place$LT$alloc..vec..Vec$LT$std..net..socket_addr..SocketAddr$GT$$GT$17hb5fdc8c3c9cf8a58E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN3std3net6parser53_$LT$impl$u20$std..net..socket_addr..SocketAddrV4$GT$11parse_ascii17hc3c94f106e08c064E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN3std3net6parser53_$LT$impl$u20$std..net..socket_addr..SocketAddrV6$GT$11parse_ascii17h5918e38a02aadf1cE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN3std3net6parser92_$LT$impl$u20$core..str..traits..FromStr$u20$for$u20$std..net..socket_addr..SocketAddrV6$GT$8from_str17h6cfb4d8bf21a891dE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN3std3net6parser51_$LT$impl$u20$std..net..socket_addr..SocketAddr$GT$11parse_ascii17hb43480db2384c46eE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN3std3net6parser90_$LT$impl$u20$core..str..traits..FromStr$u20$for$u20$std..net..socket_addr..SocketAddr$GT$8from_str17h2c6c4b774595c0d6E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN125_$LT$std..net..socket_addr..SocketAddrV4$u20$as$u20$std..sys_common..FromInner$LT$libc..unix..linux_like..sockaddr_in$GT$$GT$10from_inner17h6f0385108710a2edE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN126_$LT$std..net..socket_addr..SocketAddrV6$u20$as$u20$std..sys_common..FromInner$LT$libc..unix..linux_like..sockaddr_in6$GT$$GT$10from_inner17h8ffd10e6a39c0bf1E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN125_$LT$std..net..socket_addr..SocketAddrV4$u20$as$u20$std..sys_common..IntoInner$LT$libc..unix..linux_like..sockaddr_in$GT$$GT$10into_inner17hdd4da6195906821cE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN126_$LT$std..net..socket_addr..SocketAddrV6$u20$as$u20$std..sys_common..IntoInner$LT$libc..unix..linux_like..sockaddr_in6$GT$$GT$10into_inner17hd8b52466bf436ffcE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN116_$LT$std..net..socket_addr..SocketAddr$u20$as$u20$core..convert..From$LT$std..net..socket_addr..SocketAddrV4$GT$$GT$4from17h123d0549d57354abE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN116_$LT$std..net..socket_addr..SocketAddr$u20$as$u20$core..convert..From$LT$std..net..socket_addr..SocketAddrV6$GT$$GT$4from17h8460b5476c7c3735E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN70_$LT$std..net..socket_addr..SocketAddr$u20$as$u20$core..fmt..Debug$GT$3fmt17h5b9545923d08a289E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN74_$LT$std..net..socket_addr..SocketAddrV4$u20$as$u20$core..fmt..Display$GT$3fmt17he756afe138c2d17bE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN72_$LT$std..net..socket_addr..SocketAddrV4$u20$as$u20$core..fmt..Debug$GT$3fmt17heb518520bb281ae2E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN74_$LT$std..net..socket_addr..SocketAddrV6$u20$as$u20$core..fmt..Display$GT$3fmt17h3d4de6e9f0a2e2e6E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN72_$LT$std..net..socket_addr..SocketAddrV6$u20$as$u20$core..fmt..Debug$GT$3fmt17h5fed676461fafd1aE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN77_$LT$std..net..socket_addr..SocketAddrV4$u20$as$u20$core..cmp..PartialOrd$GT$11partial_cmp17hc14d75ce0b0abbbeE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN77_$LT$std..net..socket_addr..SocketAddrV6$u20$as$u20$core..cmp..PartialOrd$GT$11partial_cmp17h723cc45d80551a6cE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN70_$LT$std..net..socket_addr..SocketAddrV4$u20$as$u20$core..cmp..Ord$GT$3cmp17h1e937cefd991353aE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN70_$LT$std..net..socket_addr..SocketAddrV6$u20$as$u20$core..cmp..Ord$GT$3cmp17hb31a00e8d5d494aaE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN90_$LT$std..net..socket_addr..SocketAddr$u20$as$u20$std..net..socket_addr..ToSocketAddrs$GT$15to_socket_addrs17h27bc8e75134737ebE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN92_$LT$std..net..socket_addr..SocketAddrV4$u20$as$u20$std..net..socket_addr..ToSocketAddrs$GT$15to_socket_addrs17h314a4bc2e80e0181E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN92_$LT$std..net..socket_addr..SocketAddrV6$u20$as$u20$std..net..socket_addr..ToSocketAddrs$GT$15to_socket_addrs17h747fa9796c056a64E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN96_$LT$$LP$std..net..ip_addr..IpAddr$C$u16$RP$$u20$as$u20$std..net..socket_addr..ToSocketAddrs$GT$15to_socket_addrs17hd0b54b07dc831ec8E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN98_$LT$$LP$std..net..ip_addr..Ipv4Addr$C$u16$RP$$u20$as$u20$std..net..socket_addr..ToSocketAddrs$GT$15to_socket_addrs17hb008ea54a7f80222E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN98_$LT$$LP$std..net..ip_addr..Ipv6Addr$C$u16$RP$$u20$as$u20$std..net..socket_addr..ToSocketAddrs$GT$15to_socket_addrs17hcbfcf54a71f7f620E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN78_$LT$$LP$$RF$str$C$u16$RP$$u20$as$u20$std..net..socket_addr..ToSocketAddrs$GT$15to_socket_addrs17h67f8e0798ced9d7fE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN92_$LT$$LP$alloc..string..String$C$u16$RP$$u20$as$u20$std..net..socket_addr..ToSocketAddrs$GT$15to_socket_addrs17h1c129ea4ca2c9499E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN60_$LT$str$u20$as$u20$std..net..socket_addr..ToSocketAddrs$GT$15to_socket_addrs17h4014dae1a2fcffbdE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN104_$LT$$RF$$u5b$std..net..socket_addr..SocketAddr$u5d$$u20$as$u20$std..net..socket_addr..ToSocketAddrs$GT$15to_socket_addrs17hd1d40937a216b107E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN78_$LT$alloc..string..String$u20$as$u20$std..net..socket_addr..ToSocketAddrs$GT$15to_socket_addrs17hfd7ea5943bf651d8E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN101_$LT$std..os..unix..net..addr..SocketAddr$u20$as$u20$std..os..net..linux_ext..addr..SocketAddrExt$GT$16as_abstract_name17hfd5599bd108415bbE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN73_$LT$std..os..unix..net..addr..SocketAddr$u20$as$u20$core..fmt..Debug$GT$3fmt17h23abb749d1abfe3aE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN83_$LT$std..os..unix..net..ancillary..SocketAncillary$u20$as$u20$core..fmt..Debug$GT$3fmt17h21eef4d92db7123aE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN3std10sys_common3net153_$LT$impl$u20$std..sys_common..IntoInner$LT$$LP$std..sys_common..net..SocketAddrCRepr$C$u32$RP$$GT$$u20$for$u20$$RF$std..net..socket_addr..SocketAddr$GT$10into_inner17h99c89632c6179298E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN71_$LT$libc..unix..linux_like..sockaddr$u20$as$u20$core..clone..Clone$GT$5clone17hff304bbe7d0ec1a6E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN74_$LT$libc..unix..linux_like..sockaddr_in$u20$as$u20$core..clone..Clone$GT$5clone17h924d5a37eb59df67E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN75_$LT$libc..unix..linux_like..sockaddr_in6$u20$as$u20$core..clone..Clone$GT$5clone17hc3db4893f3d6d938E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN74_$LT$libc..unix..linux_like..sockaddr_ll$u20$as$u20$core..clone..Clone$GT$5clone17hadc3e63539e106b1E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN74_$LT$libc..unix..linux_like..sockaddr_un$u20$as$u20$core..clone..Clone$GT$5clone17h93f083943d35c879E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN79_$LT$libc..unix..linux_like..sockaddr_storage$u20$as$u20$core..clone..Clone$GT$5clone17hca7f39144ab54d39E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN81_$LT$libc..unix..linux_like..linux..sockaddr_vm$u20$as$u20$core..clone..Clone$GT$5clone17h1da20b1aafe4f949E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN87_$LT$libc..unix..linux_like..linux..sock_extended_err$u20$as$u20$core..clone..Clone$GT$5clone17h4545bff88979a2d5E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN80_$LT$libc..unix..linux_like..linux..sock_fprog$u20$as$u20$core..clone..Clone$GT$5clone17hb4bfefff75b85548E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN81_$LT$libc..unix..linux_like..linux..sockaddr_nl$u20$as$u20$core..clone..Clone$GT$5clone17hb3d465291c8f57edE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN82_$LT$libc..unix..linux_like..linux..sockaddr_alg$u20$as$u20$core..clone..Clone$GT$5clone17h1cc7f5632bb2deffE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN82_$LT$libc..unix..linux_like..linux..sockaddr_can$u20$as$u20$core..clone..Clone$GT$5clone17h65a8089a7c8a0c73E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN78_$LT$core..error..Source$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h61161bc0d454101fE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN56_$LT$core..error..Source$u20$as$u20$core..fmt..Debug$GT$3fmt17h112118794e09aa5eE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN66_$LT$core..slice..sort..TimSortRun$u20$as$u20$core..fmt..Debug$GT$3fmt17h43abbb23b0672b4fE` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN4core3ptr1021drop_in_place$LT$core..slice..sort..merge_sort..RunVec$LT$alloc..slice..stable_sort$LT$$LP$gimli..common..DebugInfoOffset$C$gimli..common..DebugArangesOffset$RP$$C$alloc..slice..$LT$impl$u20$$u5b$$LP$gimli..common..DebugInfoOffset$C$gimli..common..DebugArangesOffset$RP$$u5d$$GT$..sort_by_key$LT$gimli..common..DebugInfoOffset$C$addr2line..ResDwarf$LT$gimli..read..endian_slice..EndianSlice$LT$gimli..endianity..LittleEndian$GT$$GT$..parse..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$C$alloc..slice..stable_sort$LT$$LP$gimli..common..DebugInfoOffset$C$gimli..common..DebugArangesOffset$RP$$C$alloc..slice..$LT$impl$u20$$u5b$$LP$gimli..common..DebugInfoOffset$C$gimli..common..DebugArangesOffset$RP$$u5d$$GT$..sort_by_key$LT$gimli..common..DebugInfoOffset$C$addr2line..ResDwarf$LT$gimli..read..endian_slice..EndianSlice$LT$gimli..endianity..LittleEndian$GT$$GT$..parse..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$$GT$17h808680c55fdff4f0E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN4core3ptr109drop_in_place$LT$core..slice..sort..CopyOnDrop$LT$std..backtrace_rs..symbolize..gimli..elf..ParsedSym$GT$$GT$17h4039c6ba99edaf26E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN4core3ptr432drop_in_place$LT$core..slice..sort..merge_sort..BufGuard$LT$addr2line..UnitRange$C$alloc..slice..stable_sort$LT$addr2line..UnitRange$C$alloc..slice..$LT$impl$u20$$u5b$addr2line..UnitRange$u5d$$GT$..sort_by_key$LT$u64$C$addr2line..ResDwarf$LT$gimli..read..endian_slice..EndianSlice$LT$gimli..endianity..LittleEndian$GT$$GT$..parse..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$$GT$17he94947c800a95d65E` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN4core3ptr491drop_in_place$LT$core..slice..sort..merge_sort..BufGuard$LT$addr2line..function..FunctionAddress$C$alloc..slice..stable_sort$LT$addr2line..function..FunctionAddress$C$alloc..slice..$LT$impl$u20$$u5b$addr2line..function..FunctionAddress$u5d$$GT$..sort_by_key$LT$u64$C$addr2line..function..Functions$LT$gimli..read..endian_slice..EndianSlice$LT$gimli..endianity..LittleEndian$GT$$GT$..parse..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$..$u7b$$u7b$closure$u7d$$u7d$$GT$$GT$17h9ffcb8135912278fE` (dynamic_library)
* `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3/.text._ZN104_$LT$core..iter..sources..from_fn..FromFn$LT$F$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17hed0c8a16b90d5fbfE` (dynamic_library)

#### Linker process 411718

Build-script executable: `/target/debug/build/atomic-polyfill-6f5883b967109919/build_script_build-6f5883b967109919`

Working directory: `/tmp/crate-build-aarch64-w4rmjjh7/src/atomic-polyfill-1.0.3`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)
