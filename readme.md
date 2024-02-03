Following project will be used in GitHub Actions for use with [Fsu0413/openssl-externalCMake]:

| OS / Toolchain | Versions | Arch | Action | Status |
|-|-|-|-|-|
| Windows / MSVC | 2019 / 2022 | x86 / x86_64 | - | Checked to be working |
| Windows / MinGW | 12.2.0 / 13.1.0 | x86 / x86_64 | - | Checked to be working |
| Ubuntu | 20.04 / 22.04 | x86_64 | - | Checked to be working |
| macOS | 12 / 13 / 14 | x86_64 / arm64 | - | Checked to be working |
| Android NDK | r13 (1.0.2) / r17 (1.1.0) / Latest | x86 / x86_64 / arm / arm64 | - | Checked to be working |
| FreeBSD | 13.2 / 14.0 | x86_64 | [vmactions/freebsd-vm] | Checked to be working |
| OpenBSD | 7.4 | x86_64 | [vmactions/openbsd-vm] | Checked to be working |
| NetBSD | 9.3 | x86_64 | [vmactions/netbsd-vm] | Checked to be working |
| DragonFlyBSD | 6.4.0 | x86_64 | [vmactions/dragonflybsd-vm] | Checked to be working |
| Solaris | 11.4 | x86 | [vmactions/solaris-vm] | Checked to be working |

[Fsu0413/openssl-externalCMake]: https://github.com/Fsu0413/openssl-externalCMake
[vmactions/freebsd-vm]: https://github.com/vmactions/freebsd-vm
[vmactions/openbsd-vm]: https://github.com/vmactions/openbsd-vm
[vmactions/netbsd-vm]: https://github.com/vmactions/netbsd-vm
[vmactions/dragonflybsd-vm]: https://github.com/vmactions/dragonflybsd-vm
[vmactions/solaris-vm]: https://github.com/vmactions/solaris-vm

Notes:
[vmactions](https://github.com/vmactions) provides 64-bit x86_64 VM for *BSD / 32-bit x86 VM for Solaris.  
[cross-platform-actions](https://github.com/cross-platform-actions) provides 64-bit x86_64 / aarch64 VM for Free/Open/NetBSD  
[docker/setup-qemu-action](https://github.com/docker/setup-qemu-action) and [uraimo/run-on-arch-action](https://github.com/uraimo/run-on-arch-action) provides arm / riscv VM for Linux
