# ZYCode — Desktop downloads

Official Windows downloads for the **ZYCode** desktop app (formerly ZYR ZY-S1; runs the ZY-S1 model) by ZYR AI.
This repository contains **only release files** (no source code).

## Download

Get the latest version from **[Releases → Latest](https://github.com/zyragentai/zyr-releases/releases/latest)**:

| File | What it is |
|---|---|
| `ZYCode-Setup-<version>.exe` | **ZYCode Setup (recommended)** — custom ZYCode installer window: Install / Customize (folder, desktop shortcut) / progress / Launch. No admin needed. |
| `ZYCode-Setup-Classic-<version>.exe` | Classic setup wizard (fallback) — choose folder, shortcuts, launch on finish |
| `ZYCode-Portable-<version>.exe` | Portable, no install |

The app updates itself: it checks `latest.json` on the latest release at launch and every 6 hours,
downloads in the background and asks you to restart.

## Troubleshooting

- **SmartScreen "Windows protected your PC"** — builds are unsigned: click **More info → Run anyway**.
- **Installer problems** — try `ZYCode-Setup-Classic-<version>.exe`, or Portable (no install).
- **Uninstall** — Settings → Apps (or Add/Remove Programs) → ZYCode.
- **Logs for a bug report** — `%APPDATA%\ZYCode\logs\main.log`.
- **Run ZY-S1 on your PC** — click **Download ZY-S1 model** in the top bar (or Model panel / Settings). Pause, resume and cancel are supported.
- **Sign-in** — the desktop app signs in with an email code.

© 2026 ZYR AI · [zyr3.vercel.app](https://zyr3.vercel.app)
