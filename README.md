# SAOBOT – VALORANT COLORBOT EXPERIENCE (EN)

[![Saobot preview](PHOTO%20SAOBOT/images/LOGIN.png)](https://saobot.shop)

Saobot is a premium all-in-one experience inspired by Valorant. The application combines the colorbot, animated FOV overlay, aimbot, triggerbot, anti-recoil and the Arduino spoofing workflow in a single interface. Goal: showcase how to mix color-based vision, HID automation and live telemetry. Any usage outside an educational context remains the end-user's responsibility.

> ⚠️ **Educational usage only**: Saobot illustrates technical concepts (color capture, HID hooking, license handling). We do not endorse any usage that violates Riot Games' ToS. By downloading or running Saobot you accept full responsibility.

> ✅ **Inclusive setup**: the installer ships Python 3.10, configures dependencies, deploys Saobot.exe, installs the required drivers and checks automatically for an Arduino Leonardo used as the mouse controller.

---

## DEMO / INSTALLATION VIDEO

[![Demo Saobot](https://img.youtube.com/vi/XXXXXXXXXXX/maxresdefault.jpg)](https://www.youtube.com/watch?v=XXXXXXXXXXX)

> Replace `XXXXXXXXXXX` with the ID of your YouTube/Vimeo video. The thumbnail remains clickable and opens the presentation (setup, license login, module overview, etc.).

---

## WHY SAOBOT?

- **Premium experience**: animated login, Valorant-inspired theme, module-driven tabs, live telemetry.
- **Bilingual interface**: main GUI, spoofer window, and logs switch instantly between FR/EN.
- **Surgical colorbot**: dxcam/d3dshot capture, multi-shape overlay, RGB blinking, real-time transparency.
- **Composable automations**: aimbot, triggerbot, anti-recoil and offsets combine in one click with head/body/feet presets and fine-grained tuning.
- **Integrated spoofing**: flash, VID/PID cloning, HID monitoring and Arduino scripts directly inside the interface.
- **Safety**: the bot refuses to start if the Arduino board is missing, firmware is absent, or licenses are invalid.
- **Observability**: User/System panels, activity/crash logs, GUI crash reporter, capture FPS tracking.

### What's new – 2025.11

- Full localization of the spoofing tool with automatic sync to the language selector.
- Backend log/status harmonization through the shared translation system.
- Refreshed Nuitka script (`scripts/build_nuitka.ps1`) to rebuild a standalone executable in one click.

---

## MODULES SHOWCASE

- **Premium portal**: license login, Discord/store shortcuts, info cards.
	[![Login premium](PHOTO%20SAOBOT/images/LOGIN.png)](https://saobot.shop)

- **General**: capture backend selection, FPS ceiling, low-latency preview.
	[![General tab](PHOTO%20SAOBOT/images/general.png)](https://saobot.shop)
	[![General alt](PHOTO%20SAOBOT/images/geenral2.png)](https://saobot.shop)

- **FOV Overlay**: circle/square/triangle/star/heart shapes, RGB blink, dynamic stroke.
	[![FOV overlay](PHOTO%20SAOBOT/images/fov.png)](https://saobot.shop)

- **Aimbot**: X/Y speeds, offsets, preset profiles, human-like safe mode.
	[![Aimbot tab](PHOTO%20SAOBOT/images/aimbot.png)](https://saobot.shop)
	[![Aimbot presets](PHOTO%20SAOBOT/images/aimbot%202.png)](https://saobot.shop)

- **Triggerbot**: configurable zones, color filters, custom delays.
	[![Triggerbot](PHOTO%20SAOBOT/images/Triggerbot.png)](https://saobot.shop)

- **Anti-recoil**: per-weapon curves, real-time offsets.
	[![Anti recoil](PHOTO%20SAOBOT/images/Anti%20recoil.png)](https://saobot.shop)

- **Spoofing**: Arduino link, flash sketch `hardware/microcontroller/microcontroller.ino`, HID cloning.
	[![Spoofing view](PHOTO%20SAOBOT/images/spoof.png)](https://saobot.shop)

- **User/System**: license status, HWID, CPU load, capture metrics.
	[![User tab](PHOTO%20SAOBOT/images/user.png)](https://saobot.shop)

---

## HOW SAOBOT WORKS

1. **Installation**: `SaobotSetup.exe` installs Python 3.10, Saobot.exe, dependencies and configures shortcuts.
2. **Sign-in**: on launch, enter the license received after purchase at [saobot.shop](https://saobot.shop); the API secures the key via HWID + username.
3. **Hardware check**: the app blocks launch if the Arduino Leonardo is missing or the firmware is not flashed.
4. **Module setup**: tune FOV, aimbot, triggerbot, anti-recoil, spoofing… every tab stores profiles and shows telemetry.
5. **Monitoring**: live logs/notifications, user/system panel, overlay preview, capture tests, built-in crash reporter.
6. **Support**: direct buttons for Discord tickets, website, log sharing.

---

## KEY ADVANTAGES

| Axis | Saobot |
| --- | --- |
| **Interface** | Valorant-inspired UI, animations, theming, live preview |
| **Overlay** | Complex shapes, RGB blink, ultra-fine transparency |
| **Aimbot/Triggerbot** | Multiple profiles, precise offsets, stealth mode |
| **Anti-recoil** | Per-weapon curves, graphical editing |
| **Spoofing** | Built-in Arduino management, flash + clone without external CLI |
| **Security** | License server validation, HWID + username binding, mandatory Arduino check |
| **Observability** | Activity/crash logs, system panel, server status |

---

## REQUIREMENTS

- Windows 10/11 64-bit
- DirectX 11 compatible GPU (dxcam/d3dshot)
- Python 3.10 (installed automatically by the setup client)
- Arduino Leonardo (or compatible) to drive HID mouse actions
- Internet connection for license activation and profile sync

## Build the executable

1. Ensure Python 3.10 plus the dependencies in `requirements.txt` are installed.
2. Open PowerShell at the project root.
3. Run `scripts\build_nuitka.ps1` (options available: `-OutputName`, `-DisableLTO`, etc.).
4. The standalone folder is generated in `build/nuitka/<Name>.dist` with `SaobotNuitka.exe` ready for distribution.

---

## GET SAOBOT

1. Visit **[saobot.shop](https://saobot.shop)** and choose a plan.
2. After payment you receive a unique license key by email.
3. Download `SaobotSetup.exe`, install, launch the app, enter your key.
4. The license automatically locks to your HWID (1 license = 1 machine). Need to move to a new PC? Open a support ticket.

Instant support: in-app Discord button or [discord.gg/aQMcEPgUUa](https://discord.gg/aQMcEPgUUa).

---

## LOGS & SUPPORT

- `logs/activity/`: capture/module/preview history.
- `logs/crash/`: full tracebacks, exportable from the app.
- Facing an issue? Bundle both folders + a screenshot and reach the Discord support team.

---

## LEGAL WARNINGS

- Provided for educational/demo purposes. No warranty for online game usage.
- Usage may violate Riot Games or other publishers' ToS: risk of ban/sanctions.
- Resell, reverse engineering, or license sharing strictly forbidden. One license = one HWID.
- Saobot is not affiliated with Riot Games or Valorant. Any mention of the name is descriptive only.

---

© 2025 – Saobot. All rights reserved. Any distribution outside educational/demo use requires written approval.
