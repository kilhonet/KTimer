# KTimer

**A free Windows shutdown timer — when the time you set runs out, it shuts down your PC or puts it to sleep.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) takes precedence.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-2.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/ktimer?lang=en)

![KTimer screen](images/ktimer-en.webp)

## Overview

Falling asleep to a movie, or leaving a long download or backup running while you step away — sometimes you just want the PC to turn itself off when it's done.

With KTimer, set the time with a few button presses and click **Run**. A flip clock counts down to zero, then the PC shuts down. Instead of shutting down, it can also send the PC into **hibernation or sleep**.

Right before shutting down, KTimer **captures the screen and shows it to you the next time you turn the PC on.** In the morning you can see at a glance whether the download finished and which windows were open.

## Features

- **Scheduled shutdown** — From 1 minute up to 7 hours; the PC shuts down when the time runs out.
- **Hibernation · Sleep** — Put the PC to sleep instead of shutting it down. KTimer picks whichever this PC supports.
- **See the last screen** — The screen right before shutdown is saved and shown in your browser at the next startup.
- **Flip clock** — The remaining time is shown as large hours : minutes : seconds cards you can read at a glance.
- **Set the time with buttons** — `−5` `−1` `+1` `+5` add and subtract; `5` `10` `30` set the value directly.
- **Nothing to configure** — No settings window, no administrator rights; a single executable.
- **9 languages** — Korean · English · Japanese · Chinese · Russian · Italian · French · Spanish · Arabic. Follows the Windows display language.

## Download / Installation

| Type | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/ktimer?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/ktimer?lang=en&nosetup) |

With the installer, KTimer opens as soon as installation finishes and is added to the Start menu. For the portable version, unzip it and run `KTimer.exe`.

## Usage

### Basic flow

1. Start KTimer. The window opens in the middle of the screen with the clock ready at **00 : 05 : 00** (5 minutes).
2. Set the time with the time buttons. For example: `30` → 30 minutes; `30` then `+5` six times → 1 hour.
3. Check the power icon to see what will happen. The **power symbol** means shut down; click it once to switch to the **moon** for sleep.
4. Click **Run**. The clock counts down one second at a time, and the dots between the digits blink to show it's counting.
5. At zero, the button changes to **Shutting down…** (or **Hibernating…** / **Sleeping…**) and the PC shuts down or goes to sleep. KTimer closes along with it.

### Screen layout

| Element | What it does |
|---|---|
| Flip clock | Time remaining (hours : minutes : seconds). The dots blink while counting |
| `−5` `−1` `+1` `+5` | Subtract or add that many minutes |
| `5` `10` `30` | Set the time to that many minutes directly |
| Power icon | Each click toggles **Shut down** (power symbol) ↔ **Sleep** (moon). Hover to see its name |
| **Run** / **Stop** | Start / stop the countdown |

- While counting, the time buttons and the power icon hide and only **Stop** remains, so the time can't be changed by accident.
- The time range is **1 minute to 7 hours**. Going below or above simply stops at the limit.

### How to…

**Fall asleep to a movie or music**
A movie is usually around 2 hours. Press `30`, add enough with `+5`, click **Run** and go to sleep. The PC shuts down around the time it ends.

**Leave a download, backup or video conversion running**
Schedule the time the job should take, plus a little extra (up to 7 hours). The next time you turn the PC on, the last screen before shutdown opens, so you can check right away whether the job really finished.

**See what was on the screen right before shutdown**
When KTimer shuts down the PC, it saves the screen of **the monitor the mouse was on**. The next time you turn on the PC and sign in, your default browser opens and shows that screen. There's nothing you need to do.
- With several monitors, leave the mouse on the monitor with the window you want to check.
- This is only for **Shut down**. With sleep, the screen is still there when you wake the PC, so it isn't needed.

**You have unsaved documents**
When the time comes, other programs can't hold up the shutdown — the PC reliably turns off. It never gets stuck all night on a "Save changes?" prompt, but **unsaved work won't be kept**, so save before you click Run.

**Put the PC to sleep instead of shutting it down**
Before clicking Run, click the power icon to switch it to the **moon**. Hover over the icon to see what this PC will actually do.
- **Hibernation** — Saves your open windows and work, then powers off. Turning it back on returns you to where you were.
- **Sleep** — Waits using very little power. Wakes up quickly.
PCs that support hibernation use hibernation; others use sleep. KTimer checks again right before acting, so if you change power settings while it waits, it follows them.

**Cancel or change the schedule**
Click **Stop** to pause the countdown and bring the time buttons back. Adjust the time and click **Run** to start counting again from that time. To cancel entirely, you can simply close the window — closing it cancels the schedule.

**The window is in the way**
**Minimize** it — it keeps counting in the background. Open it again from the taskbar when you want to check the remaining time.

**Can't find the window**
Run KTimer again. Instead of opening a new one, the window that's already counting comes to the front (only one schedule runs at a time).

**Tips for setting the time quickly**
- For the common 5 · 10 · 30 minutes, press that button once.
- 1 hour is `30` then `+5` six times; 45 minutes is `30` then `+5` three times.
- Fine-tune by the minute with `+1` · `−1`. Pressing `−1` repeatedly never goes below 1 minute.

## Configuration

There is no settings window and nothing is saved. Every launch starts like this:

| Item | Starting value |
|---|---|
| Time | 5 minutes |
| Action | Shut down |
| Appearance | Dark theme |
| Language | Windows display language (English if it isn't supported) |

## Requirements

- Windows 10 · Windows 11 (64-bit)
- No administrator rights or extra runtime needed to run the program.
- The last-screen view opens in your default browser. The internet connection is used only for that view and for new-version notices.

## Updates

KTimer does **not** update itself. At startup it checks for a new version and shows a notice; clicking **Yes** opens the download page and closes the program. New versions are released manually after internal verification and announced on the [KTimer page](https://kilho.net/ktimer). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

**Version history**

| Version | Date | Changes |
|---|---|---|
| 2.0.0 | 2026-09-23 | Full redesign: flip clock, set the time directly with buttons, pick shutdown or sleep with an icon, colors and number font tuned for the dark interface, lighter and smoother overall |
| 1.3.2 | 2026-08-21 | Menus and behavior matched to hibernation support, improved sleep switching, improved auto-start setup and update checking |
| 1.3.1 | 2024-11-16 | Added Italian · French · Russian · Chinese |
| 1.3.0 | 2024-11-03 | Hibernation support, prevents running twice, improved multilingual support and update notices |

## License

KTimer is **freeware**. Use it free of charge anywhere — at the office, at home, in government offices, at school — and redistribute it freely.

## Links

- Website: <https://kilho.net/ktimer>
- Forum: <https://groups.google.com/g/kilhonet>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
