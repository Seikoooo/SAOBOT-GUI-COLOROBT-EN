# SAOBOT – Colorbot Auto Aiming Tool

[![Saobot preview](PHOTO%20SAOBOT/images/LOGIN.png)](https://saobot.shop)

Saobot is an all-in-one educational toolkit for learning programming, image analysis, and software automation. The application bundles a colorbot, animated FOV overlay, aimbot, triggerbot, anti-recoil, and Arduino spoofing inside a single interface. The goal is to demonstrate how to combine color-based vision, HID automations, and real-time telemetry. Any use for cheating in games is forbidden and remains solely the responsibility of the end user.

> ⚠️ **Educational use only**: Saobot showcases technical concepts (color capture, HID hooking, license management). We do not endorse any usage that breaks local laws or platform policies. By downloading or running Saobot, you agree to assume all risks and liabilities.

> ✅ **Inclusive setup**: the installer ships Python 3.10, installs dependencies, deploys Saobot.exe, the required drivers, and automatically checks for an Arduino Leonardo board for mouse control.

---

## DEMO / INSTALLATION VIDEO

[▶ Watch the Google Drive presentation](https://drive.google.com/file/d/1CGJU7LvR1S7DH6Wtj-kpz5OkbFMVpLQg/preview)

---

## WHY SAOBOT?

- **Educational experience**: animated login, modern theme, tabbed modules, live telemetry for learning.
- **Bilingual interface**: the entire panel (main GUI, spoofer, logs) switches live between FR/EN.
- **Surgical colorbot**: dxcam/d3dshot capture, multi-shape overlay, RGB blinking, real-time transparency.
- **Composable automations**: aimbot, triggerbot, anti-recoil, and offsets mix in one click with preconfigured profiles (head/body/feet) and fine-grained tweaks for studying algorithms.
- **Built-in spoofing**: flash, clone VID/PID, monitor HID, and push Arduino scripts straight from the interface to explore hardware security.
- **Safety**: the bot refuses to start if the Arduino board is missing, the firmware is absent, or the licenses are invalid.
- **Observability**: User/System panels, activity/crash logs, crash reporter GUI, capture FPS monitoring for debugging.

### Highlights 2025.11

- Complete localization of the spoofing tool and automatic sync with the language selector.
- Harmonized backend logs/status (spoofer) with the shared translation system.
- Refreshed Nuitka script (`scripts/build_nuitka.ps1`) to rebuild a standalone executable in one click.

---

## MODULES IN PICTURES

- **Premium portal**: license access, Discord/shop support, info modules.
	[![Login premium](PHOTO%20SAOBOT/images/LOGIN.png)](https://saobot.shop)

- **General**: select capture backend, FPS limits, low-latency preview.
	[![General tab](PHOTO%20SAOBOT/images/general.png)](https://saobot.shop)
	[![General alt](PHOTO%20SAOBOT/images/geenral2.png)](https://saobot.shop)

- **FOV Overlay**: circle/square/triangle/star/heart shapes, RGB blink, dynamic stroke.
	[![FOV overlay](PHOTO%20SAOBOT/images/fov.png)](https://saobot.shop)

- **Aimbot**: X/Y speeds, offsets, preset profiles, human safe-mode.
	[![Aimbot tab](PHOTO%20SAOBOT/images/aimbot.png)](https://saobot.shop)
	[![Aimbot presets](PHOTO%20SAOBOT/images/aimbot%202.png)](https://saobot.shop)

- **Triggerbot**: configurable zones, color filters, custom delays.
	[![Triggerbot](PHOTO%20SAOBOT/images/Triggerbot.png)](https://saobot.shop)

- **Anti-recoil**: curves per weapon/profile, real-time offsets.
	[![Anti recoil](PHOTO%20SAOBOT/images/Anti%20recoil.png)](https://saobot.shop)

- **Spoofing**: Arduino link, flash sketch `hardware/microcontroller/microcontroller.ino`, HID cloning.
	[![Spoofing view](PHOTO%20SAOBOT/images/spoof.png)](https://saobot.shop)

- **User/System**: license status, HWID, CPU load, capture metrics.
	[![User tab](PHOTO%20SAOBOT/images/user.png)](https://saobot.shop)

---

## HOW DOES SAOBOT WORK?

1. **Installation**: `SaobotSetup.exe` installs Python 3.10, Saobot.exe, dependencies, and configures shortcuts.
2. **Login**: on launch, enter the license received after purchasing on [saobot.shop](https://saobot.shop); the API secures the key via HWID + username.
3. **Hardware check**: the app blocks execution if the Arduino Leonardo is not detected or if the firmware is not flashed.
4. **Module setup**: tweak FOV, aimbot, triggerbot, anti-recoil, spoofing… Each tab stores your profiles and displays telemetry.
5. **Monitoring**: real-time logs/notifications, user/system panel, overlay preview, capture tests, built-in crash reporter.
6. **Support**: direct buttons to Discord (tickets), website, log sharing in one click.

---

## KEY BENEFITS

| Axis | Saobot |
| --- | --- |
| **Interface** | Modern UI, animations, themes, live preview for education |
| **Overlay** | Complex shapes, RGB blink, ultra-fine transparency |
| **Aimbot/Triggerbot** | Multiple profiles, precise offsets, safe-mode for study |
| **Anti-recoil** | Curves per weapon, graphical editing |
| **Spoofing** | Integrated Arduino management, flash + cloning without external CLI |
| **Security** | Server license checks, HWID + username binding, mandatory Arduino control |
| **Observability** | Activity/crash logs, system panel, server status |

---

## PREREQUISITES

- Windows 10/11 64-bit
- DirectX 11 capable GPU (dxcam/d3dshot)
- Python 3.10 (installed automatically by the client setup)
- Arduino Leonardo (or compatible) board to drive the mouse via HID
- Internet connection for license activation and profile sync

## Build the Executable

1. Ensure Python 3.10 and the dependencies listed in `requirements.txt` are installed.
2. Open PowerShell at the project root.
3. Run `scripts\build_nuitka.ps1` (options available: `-OutputName`, `-DisableLTO`, etc.).
4. The standalone folder is generated in `build/nuitka/<Name>.dist` with `SaobotNuitka.exe` ready to ship.

---

## GET SAOBOT

1. Visit **[saobot.shop](https://saobot.shop)** and pick a plan.
2. After payment you receive a unique license via email.
3. Download `SaobotSetup.exe`, install, launch the app, enter the key.
4. The license automatically locks to your HWID (1 license = 1 machine). To change PCs, open a support ticket.

Instant support: in-app Discord button or [discord.gg/aQMcEPgUUa](https://discord.gg/aQMcEPgUUa).

---

## LOGS & SUPPORT

- `logs/activity/`: tracks actions (capture, module, preview).
- `logs/crash/`: full tracebacks exportable from the app.
- If something goes wrong: attach both folders + a screenshot, then contact Discord support.

---

## LEGAL WARNINGS

- Product supplied for educational/demonstration purposes only. No warranty of usability in online games.
- Any use for cheating in games is prohibited and fully your responsibility. Usage may violate local laws or platform policies: risk of detection/sanctions.
- Reselling, reverse engineering, or sharing the license is strictly forbidden. One license = one HWID.
- Saobot is not affiliated with any game publisher. Any use of a name is purely descriptive.
- We decline all responsibility for legal or other consequences arising from the use of this tool.

---

© 2025 – Saobot. All rights reserved. Any distribution outside the educational scope requires written approval.
