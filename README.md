# WordSquirrel — Releases

WordSquirrel is a tray-resident vocabulary app for Windows: press a global
hotkey over any text, get a translation popup, save words to your personal
dictionary, and practice them with Leitner-style flashcards.

This repository hosts **release downloads only** — the source code lives in a
private repository.

## Download

**[Latest release — WordSquirrel installer (NSIS)](../../releases/latest)**

Run the installer and follow the wizard. Your data is stored under
`%APPDATA%\WordSquirrel` and survives updates — installing a newer version
over an existing one keeps your dictionary and settings.

## Windows SmartScreen notice

The installer is currently **not code-signed**, so on first run Windows may
show a *"Windows protected your PC"* dialog. This is expected for new,
unsigned downloads. To proceed: click **More info**, then **Run anyway**.

Only download WordSquirrel from this repository. To verify a download, every
release lists the SHA-256 checksum of its installer; compare it with:

    certutil -hashfile WordSquirrel-<version>.exe SHA256

## Updating

Download the latest installer and run it over your existing installation —
your data is migrated automatically on first launch.

## License

WordSquirrel is free to download and use for personal purposes.
The software is proprietary — source code is not public, and
redistribution of the binaries is not permitted.
All rights reserved © 2026 sz4m1mi.
