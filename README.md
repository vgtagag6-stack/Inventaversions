# Inventa Tweaks

A desktop app for tuning Windows, built with Tauri.

**This project is in progress and under active development.** The app shell,
sign-in, and updater work. The tuning sections shown in the app are placeholder
screens and are not implemented yet.

## Status

Implemented:

- Sign-in with Discord or Google.
- Signed-in dashboard with a profile menu.
- Theme selection.
- Update check that points to the newest GitHub release.
- Standard window controls.

Not implemented yet. These appear in the app as empty placeholder screens:

- System Backup
- Optimizations
- System Cleanup
- Game Tweaks
- Focus Mode
- Game Mode
- Additional settings

## Download

Installers are published on the releases page. No account or sign-in is required.

https://github.com/vgtagag6-stack/Inventaversions/releases/latest

| File | Description |
| --- | --- |
| `Inventa.Tweaks-Setup.exe` | Windows installer (recommended) |
| `Inventa.Tweaks_0.0.4_x64_en-US.msi` | Windows MSI package |
| `inventa-tweaks.exe` | Portable executable |

## Screenshot

![Inventa Tweaks](Assets/Dark.png)

## Build from source

Requires Node.js, Rust, and the Tauri prerequisites for your platform.

```bash
npm install
npm run tauri dev
npm run build
```

## Community

Discord: https://discord.gg/cDmJhHjtHQ
