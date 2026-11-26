# Compactster releases

Compactster compresses games, apps and folders on Windows and Linux so they take less disk space and still open as usual. Every file is checked, and compression can be undone with one click.

This repository holds the release files only. The easiest place to download is **[compactster.com/download](https://compactster.com/download)**.

## Which file do I need?

| System | File |
| --- | --- |
| Windows 10 and 11, most PCs | `Compactster_<version>_x64-setup.exe` |
| Windows on ARM (Snapdragon) | `Compactster_<version>_arm64-setup.exe` |
| Older 32-bit Windows | `Compactster_<version>_x86-setup.exe` |
| Installing on many PCs (Intune and similar) | the `.msi` for your PC |
| Ubuntu, Debian, Mint | `.deb` (amd64 for most PCs, arm64 for ARM) |
| Fedora, openSUSE | `.rpm` (x86_64 for most PCs, aarch64 for ARM) |
| Any Linux, no install | `Compactster_<version>_amd64.AppImage` |

Each release lists every file with its SHA-256 checksum in `SHA256SUMS.txt`.

## The first time you open it

The Windows installer is not signed yet, so Windows may show "Windows protected your PC". Choose More info, then Run anyway.

On Linux, compressing in place needs a btrfs drive. On other drives, Compactster offers the Vault instead. To run the AppImage, make it executable first: `chmod +x Compactster_*.AppImage`.

## Help

Questions and problems: [compactster.com/help](https://compactster.com/help) or support@compactster.com.

Compactster is free to use, with optional Pro. See [compactster.com/pricing](https://compactster.com/pricing). The app's source code is not in this repository.
