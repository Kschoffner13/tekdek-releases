# TekDek

Downloads for TekDek, a touchscreen stream deck built on the Freenove FNK0104N
(ESP32-S3, 3.5" display), with a Windows app to design its screens.

## Install

1. Open the [latest release](https://github.com/Kschoffner13/tekdek-releases/releases/latest)
   and download `TekDek-Setup-<version>.exe`.
2. Run it. It installs for your Windows user only, so it doesn't need admin rights.
   Windows SmartScreen may warn about an unknown publisher: click **More info** and
   then **Run anyway**.
3. Plug the dek in over USB. The TekDek agent in the system tray connects to it
   automatically and starts with Windows.
4. Open **TekDek Editor** from the Start Menu to design the dek's screens.

Requires 64-bit Windows 10 or 11.

## Updates

The TekDek app checks this page for new versions and offers to update itself and the
dek's firmware. To update by hand, download and run the newest installer. Your screens
are kept.

## Uninstall

**Settings → Apps → Installed apps → TekDek → Uninstall.** Your saved screens in
`%APPDATA%\TekDek` are kept.

---

This repository only hosts release downloads. The source code is private.
