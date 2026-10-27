<div align="center">

<img src="https://raw.githubusercontent.com/devnithdev/printbridge/main/Source%20code/installer/guide-img/printbridge-badge.png" alt="PrintBridge" width="280">

### Print from any phone or computer to any printer in the office.

No app to install on phones, no accounts. ☕ by [@devnithdev](https://github.com/devnithdev).

<br>

[![Download PrintBridge](https://img.shields.io/badge/%E2%AC%87%20Download%20PrintBridge-Download%20Page-1E6FBF?style=for-the-badge)](https://devnithdev.github.io/printbridge-updates/)
[![Windows Installer](https://img.shields.io/badge/Windows-PrintBridgeSetup.exe-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/devnithdev/printbridge-updates/releases/latest/download/PrintBridgeSetup.exe)
[![Mac Installer](https://img.shields.io/badge/macOS-PrintBridge.pkg-21A67B?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/devnithdev/printbridge-updates/releases/latest/download/PrintBridge.pkg)

</div>

---

## Screenshots

| **Print from any phone or browser** | **Preview pages & pick a printer** |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/devnithdev/printbridge/main/Source%20code/installer/proposal-img/f-home.png" alt="PrintBridge home screen" width="360"> | <img src="https://raw.githubusercontent.com/devnithdev/printbridge/main/Source%20code/installer/guide-img/preview.png" alt="Print preview and page selection" width="420"> |
| **Live print queue** | **Printable wall QR sign** |
| <img src="https://raw.githubusercontent.com/devnithdev/printbridge/main/Source%20code/installer/proposal-img/f-queue.png" alt="Live print queue" width="360"> | <img src="https://raw.githubusercontent.com/devnithdev/printbridge/main/Source%20code/installer/proposal-img/f-poster.png" alt="Wall QR sign for phones" width="360"> |

---

## Highlights

* **Zero-install mobile printing**: Scan the QR code on the office wall and print directly from Safari, Chrome, or any mobile browser on iPhone, iPad, and Android. No apps or accounts needed.
* **Google Cloud Print alternative**: Keeps all printing local to your office Wi-Fi network. No cloud subscriptions, external accounts, or documents leaving your building.
* **Cross-platform**: Seamlessly connects Windows 10/11 and macOS (Apple Silicon & Intel) machines across the local network.
* **Smart print preview & queue**: Visual preview, printer type selection (inkjet, laser, dot matrix, thermal/receipt), live queue tracking, and automatic failover.

---

## Download

Get the newest version from the **[Download Page](https://devnithdev.github.io/printbridge-updates/)** or **[Releases → Latest](https://github.com/devnithdev/printbridge-updates/releases/latest)**:

| File | For |
|---|---|
| **[`PrintBridgeSetup.exe`](https://github.com/devnithdev/printbridge-updates/releases/latest/download/PrintBridgeSetup.exe)** | Windows 10 and 11 (64-bit). If SmartScreen appears: *More info → Run anyway*. |
| `PrintBridge-<version>.dmg` | Macs (Apple Silicon and Intel). Open it, then double-click `PrintBridge.pkg`. If macOS says it can’t be opened: *System Settings → Privacy & Security → Open Anyway*. |
| **[`PrintBridge.pkg`](https://github.com/devnithdev/printbridge-updates/releases/latest/download/PrintBridge.pkg)** | The same Mac installer, without the disk image. |

Install the **main computer** first, then the **computers with printers**, then the ones that only print.

## Automatic updates

Every computer with PrintBridge 4.1.3 or newer checks this page’s latest release every few hours and installs a newer version by itself, when nothing is printing.

It only installs a release whose `latest.json` is signed with PrintBridge’s own update key (`latest.json.sig`), and only an installer whose size and SHA-256 fingerprint match the signed file. So neither a changed file here nor anything in between can put a program on the office computers.

## Source code & license

This repository holds the download page, the installers, and the signed update files. The full source code is open source at **[devnithdev/printbridge](https://github.com/devnithdev/printbridge)** under the [MIT License](LICENSE).
