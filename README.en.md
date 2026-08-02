<!-- markdownlint-disable MD033 MD041 -->

<br/>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo/akagi-logo-dark.png">
    <img alt="AkagiMS" src="assets/logo/akagi-logo-light.png" width="55%">
  </picture>
</p>

<p align="center">
  <i>「死ねば助かるのに………」 - 赤木しげる</i>
  <br/><br/>
  <b>AkagiMS</b> — built for Mahjong Soul.<br/>
  One window: the game on the left, what the AI thinks on the right.
  <br/><br/>
  <a href="../../releases/latest"><b>Download</b></a>
  ·
  <a href="https://discord.gg/Z2wjXUK8bN">Ask anything on Discord</a>
  ·
  <a href="../../issues">Report a bug</a>
</p>

<p align="center">
  <a href="../../releases"><img src="https://img.shields.io/github/v/release/shinkuan/AkagiMS?label=release&logo=github&include_prereleases" alt="Latest release" /></a>
  <a href="./LICENSE.txt"><img src="https://img.shields.io/badge/license-Apache%202.0-blue?logo=apache" alt="License: Apache-2.0" /></a>
  <a href="https://discord.gg/Z2wjXUK8bN"><img src="https://img.shields.io/discord/1192792431364673577?label=discord&logo=discord&color=7289DA" alt="Discord" /></a>
</p>

<p align="center">
  <a href="./README.md">繁體中文</a>
  ·
  <a href="./README.zh-CN.md">简体中文</a>
  ·
  <b>English</b>
</p>

<p align="center">
  <i>This repository publishes releases. The source is not here.</i>
</p>

---

<p align="center">
  <img src="assets/ss_fullauto_ingame.jpg" alt="AkagiMS playing a ranked game on its own" width="90%" />
</p>

https://github.com/user-attachments/assets/d36bc5fb-898b-43fc-8867-97ab6ba2d193

---

## Download

Grab the zip for your system from [**Releases**](../../releases/latest),
unzip it, and run the program inside.

| | File | Before you run it |
|---|---|---|
| **Windows** | `akagims-<version>-windows-x64.zip` | Run `akagi.exe`. |
| **macOS** | `akagims-<version>-macos-arm64.zip` | Run `./akagi`. Apple Silicon only; unsigned, so the first launch needs `xattr -cr <unzipped folder>` or right-click → *Open*. |
| **Linux** | `akagims-<version>-linux-x64.zip` | Run `./akagi`. Needs WebKit2GTK 4.1 — `apt install libwebkit2gtk-4.1-0` / `dnf install webkit2gtk4.1` / `pacman -S webkit2gtk-4.1`. |

## Using it

Log in to Mahjong Soul in the window that opens, and play. The panel on
the right follows the game.

The four buttons in the top-left corner are the whole app:

| | |
|---|---|
| **Off** | Nothing happens. |
| **Recommend** | Every decision ranked, drawn as tiles. You still play. |
| **Auto** | It clicks for you, at human timing. |
| **Full** | It queues ranked, plays, clears the result screens, and queues again. Pick a room, a match type and how many games, then leave it. |

While **Full** is driving, a striped curtain covers the game and takes your
clicks so nothing fights it. Switch the mode back and the curtain lifts.

---

AkagiMS grew out of [Akagi](https://github.com/shinkuan/Akagi), which
supports more platforms and runs your own bot models.
