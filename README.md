# PolyShot releases

Installers for PolyShot, the screenshot and screen recording app. This repository holds only release files, not source code.

## Which file to download

Open the [latest release](https://github.com/ppolyzos/polyshot-releases/releases/latest) and pick the file for your system:

| System | File |
|--------|------|
| macOS (Apple silicon and Intel) | `PolyShot_<version>_universal.dmg` |
| Windows (installer) | `PolyShot_<version>_x64-setup.exe` |
| Windows (portable, no install) | `PolyShot_<version>_x64_portable.zip` |

PolyShot installs per user, without admin rights, and updates itself after that.

## The other files on a release

- `.app.tar.gz`, `.sig` and `latest.json` are used by automatic updates. You don't need to download them.
- `SHA256SUMS.txt` lists checksums so you can check your download.
- **Source code (zip / tar.gz)** are added by GitHub to every release. They contain only this readme.

## First launch (unsigned builds)

- **macOS:** open the .dmg, drag PolyShot to Applications, then go to System Settings › Privacy & Security › Open Anyway.
- **Windows:** in the SmartScreen prompt choose More info › Run anyway. For the portable .zip, right-click it › Properties › Unblock before extracting.
