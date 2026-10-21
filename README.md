<p align="center">
  <img src="icon.png" width="128" alt="Screen Switcher icon">
</p>

<h1 align="center">Screen Switcher</h1>

<p align="center">
  Jump to any desktop or full-screen app on your Mac with one key.<br>
  <a href="https://github.com/nicuferezan/screen-switcher/releases/latest"><b>Download the latest DMG</b></a>
</p>

<p align="center">
  <a href="https://buymeacoffee.com/nicuferezao"><img src="https://img.shields.io/badge/Buy%20me%20a%20coffee-%E2%98%95-FFDD00?style=for-the-badge" alt="Buy me a coffee"></a>
</p>

---

## What it does

Press **⌃Q** (or your own hotkey) and a panel shows every space you have — regular desktops and full-screen apps, including both apps of a Split View — with their real icons.

- Press the app's **letter** (C = Chrome, M = MySQL…) to jump straight to it.
- Or click, use ←/→ + Enter, or the position number 1–9.
- Set your own letters: right-click an app → **Set Shortcut…**.
- Lives in the menu bar, no Dock icon. Optional launch at login.

<p align="center"><img src="screenshots/panel.png" width="800" alt="The panel: every desktop and full-screen app, with the front app's shortcuts below"></p>

### Shortcuts of the app in front

Under the spaces, the panel lists the menu shortcuts of the app you were using. Press **1–9** to run one without hunting through menus; the traffic lights minimise, zoom or close its window.

### Pick your favourite shortcuts

Menu bar icon → **Edit App Shortcuts…**: star the shortcuts you use most, drag to reorder, or add custom key combinations. The first 9 show in the panel.

<p align="center"><img src="screenshots/shortcuts-editor.png" width="640" alt="Shortcut editor with all menu shortcuts on the left and favourites on the right"></p>

### Setup in one window

Permissions, Mission Control shortcuts and the panel hotkey, each with a live status check.

<p align="center"><img src="screenshots/setup.png" width="460" alt="Setup window with Accessibility, Mission Control and hotkey checks"></p>

## Install

1. Download `ScreenSwitcher-x.y.z.dmg` from [Releases](https://github.com/nicuferezan/screen-switcher/releases/latest).
2. Open it and drag **Screen Switcher** into **Applications**.
3. Open it. The first time, macOS will block it because the app isn't notarized yet:
   - go to **System Settings → Privacy & Security** and click **Open Anyway**, or
   - run `xattr -cr "/Applications/ScreenSwitcher.app"` in Terminal.
4. Follow the **Setup** window:
   - allow **Accessibility** (needed to switch spaces),
   - enable **Mission Control** shortcuts (“Move left/right a space”, “Switch to Desktop N”),
   - the panel opens with **⌃Q**; change it from the menu bar icon → **Change Hotkey…** if you need ⌃Q elsewhere.

Requires macOS 13 Ventura or later, Apple silicon or Intel.

## Support

Screen Switcher is free. If it saves you time, [buy me a coffee ☕](https://buymeacoffee.com/nicuferezao) — it helps pay for the Apple Developer account so future versions can open without the security warning.

## Feedback

Found a bug or want a feature? [Open an issue](https://github.com/nicuferezan/screen-switcher/issues).

---

<sub>Made by <a href="https://binary.company">binary.company</a>.<br>
Screen Switcher uses undocumented macOS APIs to read the list of spaces, so a macOS update may break it until a new version is released.</sub>
