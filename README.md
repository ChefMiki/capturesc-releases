# CaptureSC

**Screenshots without the wait.** Press Print Screen, select an area or click a window, mark it up right there and paste it anywhere. CaptureSC replaces the Windows Snipping Tool with something faster and calmer.

This repository only hosts the downloads. The app is a free preview for Windows 11.

## Website

**[mikicarbre.github.io/capturesc-releases](https://mikicarbre.github.io/capturesc-releases/)**

## Download

**[Download CaptureSC for Windows](../../releases/latest/download/CaptureSC-win-x64.zip)**

## Install

1. Unzip the file anywhere, for example your Downloads folder.
2. Double-click **Install.cmd** and click **Yes** when Windows asks for permission. The installer trusts the CaptureSC preview certificate, installs the app and starts it. Don't open the .msix in the `files` folder directly; without the certificate Windows refuses it (error 0x800B010A).
3. Press **Print Screen**. CaptureSC also lives in the tray next to the clock.

**Smart App Control:** this preview is not code-signed yet. If Smart App Control is on, Windows may block CaptureSC; the installer tells you and explains how to turn it off (Windows Security → App & browser control → Smart App Control).

## What it does

- **Instant:** the frozen-screen overlay appears in about a tenth of a second.
- **Click a window** to capture exactly its edges, or drag any area. Drag the border to move it, the handles to resize, or use the arrow keys.
- **Mark it up in place:** arrows, rectangles, ellipses, highlight, text and numbered steps.
- **Redact for good:** pixels are destroyed, not just blurred, so the data cannot be recovered.
- **Saved and copied** the moment you select. Ctrl+V pastes it anywhere. A small card in the corner confirms it; click it to open the screenshot.
- **Pin to screen,** history, your own shortcuts, light and dark theme.

## Privacy

Everything stays on your computer: no account, no analytics, nothing is uploaded. Screenshots are saved to your Pictures\Screenshots folder (you can change it in Settings).

## Uninstall

Double-click **Uninstall.cmd** from the download, or right-click CaptureSC in the Start menu → **Uninstall**. Your screenshots stay where they are.

## Feedback

Found a bug or have an idea? [Open an issue](../../issues/new).
