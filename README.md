# Tir-na Nog'th

A single-player action RPG. This repository hosts the public releases, the license, and
the attribution notices. The game's source code is not published here.

## Download and play

Get the latest build from the **Releases** page. Each download is the whole game, assets
included, with nothing else to install. `SHA256SUMS` on each release lets you check a
download.

### Windows

Download `TirnaNogth-win.zip`, unzip it anywhere writable (not Program Files), and run
`tirna.exe`. Saves are written to a `saves` folder beside the exe.

Requires 64-bit Windows 10 or 11 with up-to-date GPU drivers.

The executable is not code-signed, so Windows SmartScreen may show a blue
"Windows protected your PC" notice on first launch. Click **More info**, then
**Run anyway**. This is expected for an unsigned indie build.

### macOS

Download `TirnaNogth-macos.dmg`, open it, and drag Tir-na Nog'th into Applications.
Saves are written to `~/Library/Application Support/Tir-na Nog'th`.

Requires a Mac with Apple silicon (M1 or later) and macOS 11 or later.

The app is not notarized by Apple, so macOS blocks it the first time you open it. Open
System Settings, go to Privacy & Security, and click **Open Anyway** beside Tir-na Nog'th.
Or run this once in Terminal:

    xattr -dr com.apple.quarantine "/Applications/Tir-na Nog'th.app"

## Changelog

Release-by-release notes are in `CHANGELOG.md` and on each Release.

## License

The game is provided under a personal, non-commercial license. You may download and play
it for free. You may not sell it, redistribute it, modify it, or build upon it. See
`LICENSE` for the full terms.

## Attribution

Third-party assets and their licenses are credited in `CREDITS.md`. The Rust libraries
compiled into the binary are listed in `THIRD-PARTY-NOTICES.md`. Full license texts are in
the `LICENSES/` directory.
