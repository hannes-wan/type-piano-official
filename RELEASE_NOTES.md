# Type Piano 0.1.2

**Type Piano Community Edition is the complete application and is free to download and use.** Every instrument and performance control is included without activation or feature gating.

## What stands out in this release

- On Windows, Type Piano now tries WGPU first and automatically retries with Glow when WGPU initialization fails; if neither graphics backend starts, both errors are written to the startup log.
- Windows packaging statically links the Microsoft C/C++ runtime and rejects a packaged executable that still imports an external Visual C++ runtime.
- Canonical Linux x64 AppImage, DEB, and RPM packages and the Windows x64 NSIS installer are assembled on GitHub-hosted runners with final SHA-256 checksums.
- The sampled piano bank, its pinned attribution notice, and its canonical CC BY 3.0 legal text remain part of the package-integrity gate.
- GitHub-hosted packaging is build and package-integrity evidence; it is not target-host installation, native UI, audio, or MIDI acceptance.

## Choose the right package

- **Linux x64 (APPIMAGE):** `type-piano-0.1.2-linux-x64.AppImage` — Portable Linux desktop package
- **Linux x64 (DEB):** `type-piano-0.1.2-linux-x64.deb` — Debian, Ubuntu, Mint, and compatible systems
- **Linux x64 (RPM):** `type-piano-0.1.2-linux-x64.rpm` — Fedora, RHEL, openSUSE, and compatible systems
- **Windows x64:** `type-piano-0.1.2-windows-x64-setup.exe` — Guided Windows installer

## Before you install

- Computer keys, MIDI messages, audio rendering, streamed samples, and interface preferences stay in the local desktop workflow.
- Keep the installer filename and checksum together when handing a package to another machine.
- Read the [help center](https://hannes-software.com/type-piano/help/) for supported inputs, workflow boundaries, and troubleshooting.
- The complete application is free; there is no licensed feature tier to activate.

Full product details: https://hannes-software.com/type-piano/
