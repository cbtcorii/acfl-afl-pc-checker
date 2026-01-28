# ACFL & AFL PC Checker

Official anti-exploit utility for ACFL & AFL leagues.

🔵 Discord:
- https://discord.gg/afl
- https://discord.gg/acfl

---

## Features
- Full GUI (blue & white theme)
- Roblox exploit log scanning
- Activity timeline (process + prefetch)
- Session duration tracking
- Bootstrapper detection (Fishstrap, Froststrap, Voidstrap)
- USB device history scanner
- Discord webhook reporting
- Auto-updating EXE via GitHub

---

## How Auto-Update Works
1. App checks `latest.json`
2. Compares local version
3. Downloads new EXE if available
4. Backs up old EXE
5. Replaces safely and restarts

No remote code execution. No background updates.

---

## Build Instructions
```bash
pip install pyinstaller psutil requests
pyinstaller --onefile --noconsole --name "ACFL_AFL_PC_Checker" acfl_afl_pc_checker.py
