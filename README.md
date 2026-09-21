# DevFlow Studio — Releases

Binary installers for DevFlow Studio's desktop app. No source code here — see
the [Releases](https://github.com/maortegas/devflow-releases/releases) page
to download the latest version, or the
[download page](https://devflow-download.onrender.com) for the full install
manual (requirements, activation, and the harness CLIs DevFlow Studio needs).

## macOS

- Requires macOS 11 (Big Sur) or later.
- Two builds per release: Apple Silicon (`*.arm64.dmg`) and Intel (`*.x64.dmg`).
- Not code-signed yet — first launch shows a Gatekeeper warning. See the
  [download page](https://devflow-download.onrender.com#downloads) for the
  exact fix (it depends on which of the two Gatekeeper messages you get).

## Windows

- Requires Windows 10 (64-bit) or later.
- Three installers per release: a universal one (`*.exe`, works on both
  architectures) and two architecture-specific ones (`*.x64.exe`,
  `*.arm64.exe`) if you'd rather match your CPU exactly.
- Not code-signed yet — first launch shows a SmartScreen warning ("Windows
  protected your PC"). Click **More info** → **Run anyway**.
- Uninstall goes through the normal **Settings → Apps** (or Control Panel)
  like any other Windows app — no manual cleanup should be needed. If an
  older install ever gets stuck, closing DevFlow Studio completely before
  uninstalling avoids the file-lock issue that used to cause that.
