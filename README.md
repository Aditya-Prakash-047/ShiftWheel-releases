# ShiftWheel

[![Download](https://img.shields.io/badge/download-latest-FF5200)](https://github.com/Aditya-Prakash-047/ShiftWheel-releases/releases/latest)
![Windows 10/11](https://img.shields.io/badge/Windows-10%2F11-0078D4)
![macOS 11+](https://img.shields.io/badge/macOS-11%2B-555555)

**Drag a file, tap a key, drop it on the wheel.** Convert it, compress it, edit it, print it or share it, right where you are. Everything happens on your computer; nothing is uploaded.

![ShiftWheel themes](assets/themes.png)

This page has downloads, release notes and support. The source code isn't kept here.

## Download

**[Get the latest version](https://github.com/Aditya-Prakash-047/ShiftWheel-releases/releases/latest)**

| File | For |
|---|---|
| `ShiftWheel-Setup.exe` | Windows 10/11 (recommended) |
| `ShiftWheel.exe` | Windows, portable, no install |
| `ShiftWheel-mac-apple-silicon.dmg` | macOS 11+, M1 and later |
| `ShiftWheel-mac-intel.dmg` | macOS 11+, Intel |

Ignore the "Source code" links on the release page: GitHub adds them to every release, and here they contain only this page's documents.

## Install

**Windows:** run `ShiftWheel-Setup.exe`. No admin rights needed. The app isn't code-signed yet, so choose **More info → Run anyway** the first time.

**macOS:** open the `.dmg` and drag ShiftWheel onto Applications. The app isn't notarized yet: open it once, then go to **System Settings → Privacy & Security → Open Anyway**. Or run this in Terminal:

```bash
curl -fsSL https://github.com/Aditya-Prakash-047/ShiftWheel-releases/releases/latest/download/install-mac.sh | bash
```

## Use it

1. Start dragging a file in File Explorer or Finder.
2. While dragging, tap **Shift** to convert, **Ctrl** (Command on a Mac) for tools, or **Alt** (Control on a Mac) for actions.
3. Drop it on a slice. The result is saved next to the original, which is never changed.

Or select a file and press **Ctrl+Alt+W**. Keys, themes, sounds and more are in Settings, from the tray or menu-bar icon.

## Updates

ShiftWheel checks this page once a day, verifies the download's SHA-256, installs it and restarts. You can turn this off in Settings → Behaviour. Anyone on version 1.2.0 or older needs to install a newer version by hand once.

## Help

- [Report a problem](https://github.com/Aditya-Prakash-047/ShiftWheel-releases/issues/new/choose), or use About → Report a problem in the app, which fills in your version.
- [What's changed](CHANGELOG.md)
- [Security and privacy](SECURITY.md)
- [Licence](LICENSE) and [third-party notices](THIRD-PARTY-NOTICES.md)
