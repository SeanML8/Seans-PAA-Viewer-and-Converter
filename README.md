# DayZ PAA Viewer

A fast, lightweight texture viewer and converter for DayZ modding. Built as a cleaner, more user-friendly alternative to Bohemia's TexView.

![Windows](https://img.shields.io/badge/platform-Windows-blue)

## Why?

Bohemia's TexView works, but it's clunky, outdated, and painful to use for everyday texture work. DayZ PAA Viewer is designed to be what TexView should have been — a simple tool that gets out of your way and lets you focus on your textures.

- **Clean dark/light UI** — no bloated menus or confusing options
- **Instant navigation** — arrow keys or buttons to flip through textures in a folder
- **Zoom & pan** — scroll to zoom, drag to pan, just like any modern image viewer
- **Fast** — background loading with smart caching so you're never waiting around
- **Batch conversion** — convert entire folders of PAA to PNG (or PNG to PAA) in one click
- **Auto-detects DayZ Tools** — scans your Steam libraries automatically, no manual setup needed
- **Single exe** — no install, no dependencies, just download and run

## Download

Grab the latest `DayZ PAA Viewer.exe` from the [Releases](../../releases) page.

## Usage

1. Run `DayZ PAA Viewer.exe`
2. Open a file or folder containing textures
3. Browse with arrow keys or prev/next buttons
4. Scroll to zoom, drag to pan
5. Convert between PAA and PNG as needed

### Supported Formats

- `.paa` (DayZ/Arma texture format — requires DayZ Tools)
- `.png`, `.tga`, `.jpg`, `.jpeg`, `.bmp`

## Requirements

- **Windows 10/11**
- **DayZ Tools** (free on Steam under `Library > Tools > DayZ Tools`) — required for PAA conversion. The app will auto-detect the install path or prompt you to install it.

## Building from Source

```
pip install Pillow pyinstaller
pyinstaller --onefile --windowed --name "DayZ PAA Viewer" paa_viewer.py
```

The exe will be in the `dist/` folder.

## License

MIT

---

*Built with <3 by Sean*
