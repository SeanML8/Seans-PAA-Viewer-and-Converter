# Seans PAA Viewer and Converter

A texture viewer and converter for DayZ modding. Basically what Bohemia's Tex View should have been.

![Windows](https://img.shields.io/badge/platform-Windows-blue)

## Why?

Tex View is clunky and outdated. This is a simple, modern alternative that just works.

- **Dark/light mode**
- **Arrow key navigation** through all textures in a folder
- **Zoom & pan** with scroll and drag
- **Batch conversion** for entire folders (PAA to PNG or PNG to PAA)
- **Auto-detects DayZ Tools** from your Steam install
- **Single exe**, just download and run

## Download

Grab `Seans PAA Viewer and Converter.exe` from the [Releases](../../releases) page.

## Usage

1. Run `Seans PAA Viewer and Converter.exe`
2. Open a file or folder
3. Arrow keys to browse, scroll to zoom, drag to pan
4. Convert between PAA and PNG as needed

### Supported Formats

- `.paa` (requires DayZ Tools)
- `.png`, `.tga`, `.jpg`, `.jpeg`, `.bmp`

## Requirements

- **Windows 10/11**
- **DayZ Tools** (free on Steam under `Library > Tools > DayZ Tools`) for PAA conversion. Auto-detected, or you'll be prompted to install it.

## Building from Source

```
pip install Pillow pyinstaller
pyinstaller --onefile --windowed --name "Seans PAA Viewer and Converter" paa_viewer.py
```

Output goes to the `dist/` folder.

## License

MIT

*Built with <3 by Sean*
