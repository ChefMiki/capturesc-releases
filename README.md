# Snipito

**Screenshots without the wait.** Press Print Screen, select an area or click a window, mark it up right there and paste it anywhere. Snipito replaces the Windows Snipping Tool with something faster and calmer. It was called CaptureSC until version 0.1.

This repository only hosts the downloads. The app is a free preview for Windows 11.

## Website

**[chefmiki.github.io/capturesc-releases](https://chefmiki.github.io/capturesc-releases/)**

## Download

**[Download Snipito for Windows](../../releases/latest/download/Snipito-win-x64.zip)**

## Install

1. Unzip the file anywhere, for example your Downloads folder.
2. Double-click **Install.cmd** and click **Yes** when Windows asks for permission. The installer trusts the Snipito preview certificate, installs the app and starts it. Don't open the .msix in the `files` folder directly; without the certificate Windows refuses it (error 0x800B010A).
3. Press **Print Screen**. Snipito also lives in the tray next to the clock.

**Coming from CaptureSC 0.1?** Install over it; your screenshots and settings stay. From version 0.2 on, Snipito updates itself: open **What's new** in the app and click **Check for updates**.

**Smart App Control:** this preview is not code-signed yet. If Smart App Control is on, Windows may block Snipito; the installer tells you and explains how to turn it off (Windows Security → App & browser control → Smart App Control).

## What it does

- **Instant:** the frozen-screen overlay appears in about a tenth of a second.
- **Click a window** to capture exactly its edges, or drag any area. Drag the border to move it, the handles to resize, or use the arrow keys.
- **Mark it up in place:** arrows, rectangles, ellipses, highlight, text and numbered steps.
- **Redact for good:** pixels are destroyed, not just blurred, so the data cannot be recovered.
- **Editor:** crop, add a background, drop in another image, save as a project and keep editing later.
- **Scrolling capture** of long pages, **Copy text** from any area, **color picker** (C) and **ruler** (M).
- **Right-click any picture in File Explorer:** Edit with Snipito, Pin to screen, Copy text, Add background.
- **Saved and copied** the moment you select. Ctrl+V pastes it anywhere. A card in the corner confirms it.
- **Pin to screen,** history, your own shortcuts, light and dark theme.

## Privacy

Everything stays on your computer: no account, no analytics, nothing is uploaded. Screenshots are saved to your Pictures\Screenshots folder (you can change it in Settings). Snipito goes online only when you click **Check for updates**, and then it only reads the public release list on GitHub.

## Uninstall

Double-click **Uninstall.cmd** from the download, or right-click Snipito in the Start menu → **Uninstall**. Your screenshots stay where they are.

## Feedback

Found a bug or have an idea? [Open an issue](../../issues/new).
