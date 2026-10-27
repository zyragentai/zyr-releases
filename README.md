# ZYR ZY-S1 — Desktop downloads

Official Windows downloads for the **ZYR ZY-S1** desktop app by ZYR AI.
This repository contains **only release files** (no source code).

## Download

Get the latest version from **[Releases → Latest](https://github.com/zyragentai/zyr-releases/releases/latest)**:

| File | What it is |
|---|---|
| `ZYR-ZY-S1-Installer-<version>.exe` | ZYR Setup — custom installer (recommended) |
| `ZYR-ZY-S1-Setup-<version>.exe` | Classic setup wizard (also used for silent auto-updates) |
| `ZYR-ZY-S1-Portable-<version>.exe` | Portable, no install |

The app updates itself: it checks `latest.json` on the latest release at launch and every 6 hours,
downloads in the background and asks you to restart.

Builds are unsigned for now — if Windows SmartScreen warns, choose **More info → Run anyway**.

## Troubleshooting

- **SmartScreen "Windows protected your PC"** — builds are unsigned: click **More info → Run anyway**.
- **ZYR Setup shows "Preparing Setup…" for a while** — on first launch it unpacks itself (up to ~1 minute, longer while antivirus scans). Wait for the window; don't start it twice.
- **ZYR Setup still doesn't open** — use the classic `ZYR-ZY-S1-Setup-<version>.exe` instead (fastest, most compatible), or `Portable`.
- **Logs for a bug report** — installer: `%TEMP%\ZYR-Setup.log`; app: `%APPDATA%\ZYR ZY-S1\logs\main.log`.
- **Sign-in** — the desktop app signs in with an email code.

© 2026 ZYR AI · [zyr3.vercel.app](https://zyr3.vercel.app)
