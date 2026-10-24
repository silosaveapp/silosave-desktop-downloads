# SiloSave Desktop

**Save supported videos and media directly to your computer.**

SiloSave Desktop is a local-first download manager for individual media, batch jobs, and supported account backups. Keep track of your downloads in one place and process video and audio locally.

**[Explore SiloSave Desktop](https://silosave.com/desktop)** · **[Try the free SiloSave Web app](https://silosave.com/)** · **[Report an issue](https://github.com/silosaveapp/silosave-desktop-downloads/issues/new)**

## Official downloads

This repository distributes official SiloSave Desktop installers. The application source code is not published here.

| Platform | Release | Download |
| --- | --- | --- |
| Windows x64 | v0.1.8 | [Download Windows installer (.exe)](https://github.com/silosaveapp/silosave-desktop-downloads/releases/download/v0.1.8/SiloSave-Desktop-Setup-0.1.8.exe) |
| macOS 13+, Apple Silicon (M-series) | v0.1.7 preview | [Download Apple Silicon preview (.dmg)](https://github.com/silosaveapp/silosave-desktop-downloads/releases/download/v0.1.7/SiloSave-Desktop-0.1.7-mac-arm64-preview.dmg) |
| macOS 13+, Intel | v0.1.7 preview | [Download Intel preview (.dmg)](https://github.com/silosaveapp/silosave-desktop-downloads/releases/download/v0.1.7/SiloSave-Desktop-0.1.7-mac-x64-preview.dmg) |

> **macOS note:** v0.1.8 is currently Windows-only. For macOS, use the v0.1.7 preview packages listed above.

Read the [v0.1.8 release notes](https://github.com/silosaveapp/silosave-desktop-downloads/releases/tag/v0.1.8) and verify that the Windows installer SHA-256 equals `ee23d410d9382d8709db1dd6a13b93f01ff8cc75ee63c43953a0122497f7bced`. For the macOS preview builds, refer to the [v0.1.7 checksum file](https://github.com/silosaveapp/silosave-desktop-downloads/releases/download/v0.1.7/SHA256SUMS.txt). On Windows, you can calculate a file's SHA-256 with:

```powershell
Get-FileHash -Algorithm SHA256 .\SiloSave-Desktop-Setup-0.1.8.exe
```

Compare the reported hash with the published SHA-256 above before running the installer.

## Why SiloSave Desktop?

- **Batch downloads:** Handle multiple supported media links, collections, and account content.
- **Local-first:** Save downloaded files to your own computer, with local video/audio processing where needed.
- **Download management:** Choose a destination and track queued, completed, failed, or cancelled tasks.
- **Browser-assisted access:** Use an embedded browser when a supported site requires your own authorized login.

Platform support and individual formats vary. Always download content you own, created, or have permission or another legal right to save. SiloSave does not grant access to private media or bypass DRM.

## Web vs. Desktop

**[SiloSave Web](https://silosave.com/)** is the free browser-based tool for supported public links. **[SiloSave Desktop](https://silosave.com/desktop)** is a separately licensed desktop application for larger download jobs and local task management. A Desktop purchase is not required to use the website.

## macOS preview notes

The v0.1.7 macOS builds are previews, not notarized Apple releases. Read the [release notes](https://github.com/silosaveapp/silosave-desktop-downloads/releases/tag/v0.1.7) for the current compatibility and installation details.

## Support and licensing

For product information and licensing, see **[silosave.com/desktop](https://silosave.com/desktop)**. For reproducible bugs, [open an issue](https://github.com/silosaveapp/silosave-desktop-downloads/issues/new) with your app version, operating system, and steps to reproduce. Remove cookies, license codes, private URLs, and other sensitive information from screenshots or logs before posting.

This is an official **binary distribution repository**, not an open-source release of the desktop application's code.
