# Jarvis for Mac — releases

This repo only holds the update manifest for **Jarvis**, a menu-bar voice assistant for macOS. It has no source code and no keys.

* `latest.json` is read by the app on launch, every 6 hours, and from **Check for Updates…**. It lists the version, the download for each chip, and its SHA-256.
* The app checks the SHA-256 and the signing certificate (`Jarvis Self-Signed`) before it installs anything.

## Current version: 1.3.0 (2026-11-02)

| Mac | Download |
|---|---|
| Apple Silicon (M1–M4) | [Jarvis-mac-arm64.zip](https://drive.google.com/file/d/1DDwMqyHsku0ZgArLOH850Han46DiWHsW/view) |
| Intel | [Jarvis-mac-x64.zip](https://drive.google.com/file/d/1w-ak32kRgZVTNAH0mn6IcYXTgEvHUYAN/view) |

SHA-256:
- arm64 `ed47a702bfbef0099b76f3950f8f0be97f2d3380f44c039e20ee35c92b804cae`
- x64 `6a42d92c93d437d392efc151aa8b30ed78db906a8ce0c3fd4b47ec13c09c37ba`
