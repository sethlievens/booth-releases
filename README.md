# Booth

Installer and automatic updates for **Booth**, a simple audiobook recorder for Windows (Behringer UMC interface, ACX-ready MP3s).
This repository only holds the releases; there's no source code here.

## Install

1. Download **[Booth-win-Setup.exe](https://github.com/sethlievens/booth-releases/releases/latest/download/Booth-win-Setup.exe)**.
2. Run it. Windows may say "Windows protected your PC" because the installer isn't signed: click **More info**, then **Run anyway**.
3. Booth opens and puts a shortcut on the desktop and in the Start menu.

## Updates

Booth checks here every few hours. A new version downloads in the background and installs the next time Booth is closed, so it never interrupts a recording.

Recordings live in `Documents\Booth` and settings in `%AppData%\Booth`; installing, updating or uninstalling never touches them.
