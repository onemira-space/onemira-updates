# onemira-updates

Public update feeds for the OneMira desktop app.

- `mira-context/macos/appcast.xml` — Sparkle update manifest, served via GitHub Pages at `https://updates.onemira.com/mira-context/macos/appcast.xml`.
- `mira-context/windows/stable.json` — Tauri v2 Windows stable-channel manifest, served via GitHub Pages at `https://updates.onemira.com/mira-context/windows/stable.json`.
- Update ZIP archives are uploaded as assets to this repository's **Releases**, with URLs such as
  `https://github.com/onemira-space/onemira-updates/releases/download/<tag>/OneMira-<ver>.zip`.
- Windows NSIS installers and their `.sig` files are also uploaded as release assets.
  The manifest's `windows-x86_64.signature` field contains the full contents of the `.sig` file.

Source code is maintained separately in the private `onemira-space/mira-context` repository.
