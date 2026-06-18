# Claude Assist

**Desktop companion app for Claude Code** — built by [KVRNL](https://github.com/kvrnl).

Stay connected to your Claude Code sessions without being chained to the terminal. Claude Assist runs quietly on your desktop, keeping you informed and in control.

---

## What It Does

- **Desktop Notifications** — popups when Claude needs your attention, with actionable responses (yes/no, multiple choice)
- **Session Management** — discover, bookmark, lock, auto-restart, and monitor all your Claude Code sessions
- **Live Session Peek** — real-time view of what Claude is doing right now (status, tools, files, tokens)
- **Session Autopilot** — detects unanswered questions and lets you respond without switching windows
- **Neural Link** — AI chat dock with persistent memory, powered by Claude Code
- **Session Map** — force-directed graph visualization of your sessions
- **Analytics Dashboard** — usage stats, response times, peak hours, activity heatmaps
- **Task Board** — Kanban-style task management (TODO / IN PROGRESS / DONE)
- **AI Process Monitor** — monitors running processes with baseline learning and anomaly detection
- **System Monitor** — live CPU, RAM, and disk usage
- **Discord Integration** — Rich Presence status and webhook timeout alerts
- **Smart Notifications** — scheduled, recurring, file/folder watchers, smart snooze, custom sounds, text-to-speech
- **Clipboard Bridge** — queue and direct-copy clipboard integration
- **Auto-Updater** — silent download, install, and restart from GitHub Releases
- **Crash Reporting** — automatic error reporting with diagnostics
- **Global Hotkeys** — Ctrl+Shift+C/N/S/P for instant access
- **Command Palette** — Ctrl+Shift+P to search and launch anything
- **System Tray** — runs quietly in the background
- **Multi-Monitor** — popups appear on the correct monitor
- **Screenshot Capture** — built-in screen capture tool
- **Obsidian Vault Templates** — starter vaults for Business/Dev and Student workflows

---

## Install

1. Download the latest installer from the [Releases](https://github.com/kvrnl/claude-assist/releases) page
2. Run the installer
3. Launch Claude Assist from the Start Menu or Desktop shortcut

Requires Windows 10/11. Updates are automatic — the app checks for new versions and installs them silently.

### Windows SmartScreen & Antivirus

Because Claude Assist is an independent app without a paid code-signing certificate, Windows SmartScreen may show a warning the first time you run the installer. This is normal for any new/unsigned software — it's not a virus.

**Windows SmartScreen ("Windows protected your PC"):**
1. Click **"More info"**
2. Click **"Run anyway"**

**Antivirus false positives:** Some antivirus software (Windows Defender, etc.) may flag PyInstaller-built executables as suspicious. This is a [well-known PyInstaller issue](https://github.com/pyinstaller/pyinstaller/issues/6754) — it happens because PyInstaller bundles Python into a self-extracting executable, which matches patterns some AV engines look for. If your antivirus quarantines the file, add an exception for the Claude Assist install directory (default: `C:\Users\<you>\AppData\Local\Programs\Claude Assist\`).

The app is open-source-free to inspect — it's built with Python and Tkinter, nothing shady.

---

## Requirements

- Windows 10 or 11
- [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code) installed and authenticated
- No additional dependencies — everything is bundled in the installer

---

## Links

- [Latest Release](https://github.com/kvrnl/claude-assist/releases/latest)
- [Report an Issue](https://github.com/kvrnl/claude-assist/issues)

## License

Claude Assist is proprietary software developed and published by KVRNL. All rights reserved.

You are granted a free, non-exclusive, non-transferable license to download, install, and use Claude Assist for personal or commercial use. You may not reverse-engineer, decompile, modify, redistribute, or resell the software in whole or in part without prior written permission from KVRNL.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL KVRNL BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY ARISING FROM THE USE OF THE SOFTWARE.

Copyright 2026 KVRNL. All rights reserved.

---

Made by **KVRNL**
