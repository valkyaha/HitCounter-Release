# VNoHitTracker

A no-hit run tracker for Souls-like games, designed for speedrunners and challenge runners.

[![Latest Release](https://img.shields.io/github/v/release/valkyaha/HitTracker-Release)](https://github.com/valkyaha/HitTracker-Release/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/valkyaha/HitTracker-Release/total)](https://github.com/valkyaha/HitTracker-Release/releases)

## Downloads

Download the latest version from [**Releases**](https://github.com/valkyaha/HitTracker-Release/releases/latest)

| File | Description |
|------|-------------|
| `VNoHitTracker_x.x.x_portable.zip` | Portable version (no installation) |
| `VNoHitTracker_x.x.x_x64-setup.exe` | NSIS Installer (recommended) |
| `VNoHitTracker_x.x.x_x64_en-US.msi` | MSI Installer |

## Features

- **Hit Tracking** - Track hits across boss fights
- **Autosplitter** - Automatic boss detection via memory reading
- **Multi-Run Mode** - Track multiple games in sequence (Trilogy, God Runs)
- **OBS Integration** - Customizable overlays via browser source
- **Personal Bests** - Statistics tracking and comparisons
- **Plugin System** - Add support for new games via TOML plugins

## Supported Games

- Dark Souls Remastered
- Dark Souls II: Scholar of the First Sin
- Dark Souls III
- Sekiro: Shadows Die Twice
- Elden Ring
- Armored Core 6

## Quick Start

1. Download and extract/install VNoHitTracker
2. Launch the application
3. Select a game and boss preset from the Games view
4. Start your run!

## Hotkeys

| Key | Action |
|-----|--------|
| **Numpad +** | Add hit |
| **Numpad -** | Undo hit |
| **Numpad 0** | Boss defeated (next split) |
| **Numpad *** | Reset run |
| **Numpad Enter** | Start/Stop timer |

## OBS Integration

1. Go to OBS Integration view
2. Click "Start Server" (default port: 9876)
3. In OBS, add a Browser Source with URL: `http://localhost:9876`

## Documentation

- [Home](docs/Home.md) - Overview and quick links
- [Creating Plugins](docs/Creating-Plugins.md) - Add support for new games
- [Autosplitter Guide](docs/Autosplitter-Guide.md) - How the autosplitter works
- [SDK Reference](docs/SDK-Reference.md) - API documentation
- [Flag Algorithms](docs/Flag-Algorithms.md) - Memory reading algorithms
- [Language SDK](docs/LANGUAGE_SDK.md) - Create translations
- [Plugin SDK](docs/PLUGIN_SDK.md) - Plugin development guide

## System Requirements

- Windows 10/11 (64-bit)
- ~50MB disk space

## Antivirus Notes

The executable is not code-signed, which may cause antivirus software to flag it. This is a false positive - you may need to add an exception.

## License

MIT License
