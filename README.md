# PrintBridge – installers and updates

Print from any phone or computer to any printer in the office. By @devnithdev.

## Download

Get the newest version from **[Releases → Latest](https://github.com/devnithdev/printbridge-updates/releases/latest)**:

| File | For |
|---|---|
| `PrintBridgeSetup.exe` | Windows 10 and 11 (64-bit). If SmartScreen appears: More info → Run anyway. |
| `PrintBridge-<version>.dmg` | Macs (Apple Silicon and Intel). Open it, then double-click PrintBridge.pkg. If macOS says it can’t be opened: System Settings → Privacy & Security → Open Anyway. |
| `PrintBridge.pkg` | The same Mac installer, without the disk image. |

Install the main computer first, then the computers with printers, then the ones that only print.

## Automatic updates

Every computer with PrintBridge 4.1.3 or newer checks this page’s latest release every few hours and installs a newer version by itself, when nothing is printing.

It only installs a release whose `latest.json` is signed with PrintBridge’s own update key (`latest.json.sig`), and only an installer whose size and SHA-256 fingerprint match the signed file. So neither a changed file here nor anything in between can put a program on the office computers.

This repository holds only the installers and those two files; the source code is kept privately.
