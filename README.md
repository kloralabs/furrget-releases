# Furrget releases

_Furrget me not!_ Furrget by Klora records a meeting and writes the minutes, where every point traces back to what was
said.

## Download the newest build

**Desktop preview 2 (2026-10-01)**: a test build of the new app for Mac and Windows.

| Computer                                    | Download                                                                                                                                                                                      |
| ------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mac with Apple silicon, macOS 14.2 or later | [Furrget for Mac (.dmg, 291 MB)](https://github.com/kloralabs/furrget-releases/releases/download/desktop-preview-2026-10-01-2/Furrget-desktop-preview-2026-10-01-2-mac-arm64.dmg)             |
| Windows 10 (22H2) or 11, 64-bit             | [Furrget for Windows (.exe, 239 MB)](https://github.com/kloralabs/furrget-releases/releases/download/desktop-preview-2026-10-01-2/Furrget-desktop-preview-2026-10-01-2-windows-x64-setup.exe) |

What changed and known issues:
[release notes](https://github.com/kloralabs/furrget-releases/releases/tag/desktop-preview-2026-10-01-2).

## Opening it the first time

- **Mac:** open the `.dmg` and drag Furrget to Applications. The build is not notarized yet, so the first time you open
  it, go to System Settings → Privacy & Security and click **Open Anyway**.
- **Windows:** the installer is not signed yet. When SmartScreen warns you, click **More info** → **Run anyway**.

## Older builds

All builds are on the [releases page](https://github.com/kloralabs/furrget-releases/releases). `v0.1.0` (marked
Latest) is the previous Mac-only app; it checks this repo's `furrget-appcast.xml` for its updates.

Source code is private. Releases are published from `kloralabs/furrget`.
