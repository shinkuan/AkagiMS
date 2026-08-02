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
  <b>AkagiMS</b> — 專為雀魂打造。<br/>
  一個視窗：左邊是遊戲，右邊是 AI 的判斷。
  <br/><br/>
  <a href="../../releases/latest"><b>下載</b></a>
  ·
  <a href="https://discord.gg/Z2wjXUK8bN">到 Discord 問任何問題</a>
  ·
  <a href="../../issues">回報問題</a>
</p>

<p align="center">
  <a href="../../releases"><img src="https://img.shields.io/github/v/release/shinkuan/AkagiMS?label=release&logo=github&include_prereleases" alt="Latest release" /></a>
  <a href="./LICENSE.txt"><img src="https://img.shields.io/badge/license-Apache%202.0-blue?logo=apache" alt="License: Apache-2.0" /></a>
  <a href="https://discord.gg/Z2wjXUK8bN"><img src="https://img.shields.io/discord/1192792431364673577?label=discord&logo=discord&color=7289DA" alt="Discord" /></a>
</p>

<p align="center">
  <b>繁體中文</b>
  ·
  <a href="./README.zh-CN.md">简体中文</a>
  ·
  <a href="./README.en.md">English</a>
</p>

<p align="center">
  <i>這個 repo 只發布程式，原始碼不在這裡。</i>
</p>

---

<p align="center">
  <img src="assets/ss_fullauto_ingame.jpg" alt="AkagiMS 正在自己打一局段位戰" width="90%" />
</p>

https://github.com/user-attachments/assets/d36bc5fb-898b-43fc-8867-97ab6ba2d193

---

## 下載

到 [**Releases**](../../releases/latest) 下載你的系統的壓縮檔，解壓執行裡面的程式即可。

| | 檔案 | 執行前要知道的事 |
|---|---|---|
| **Windows** | `akagims-<版本>-windows-x64.zip` | 執行 `akagi.exe`。 |
| **macOS** | `akagims-<版本>-macos-arm64.zip` | 執行 `./akagi`。僅限 Apple Silicon；程式未簽章，第一次要先 `xattr -cr <解壓出來的資料夾>`，或用右鍵 → 開啟。 |
| **Linux** | `akagims-<版本>-linux-x64.zip` | 執行 `./akagi`。需要 WebKit2GTK 4.1——`apt install libwebkit2gtk-4.1-0` / `dnf install webkit2gtk4.1` / `pacman -S webkit2gtk-4.1`。 |

## 怎麼用

在開啟的視窗裡登入雀魂，然後照常打。右邊的面板會跟著牌局走。

左上角那四顆按鈕就是這個程式的全部：

| | |
|---|---|
| **關** | 什麼都不做。 |
| **推薦** | 每個決策都排序列出，用牌面畫給你看。牌還是你自己打。 |
| **自動** | 它幫你點，用接近真人的節奏。 |
| **全自動** | 自己排段位戰、打完、關掉結算畫面、再排下一局。選好房間、賽制和局數就可以走人。 |

**全自動**進行中時，畫面上會蓋一層斜紋簾幕接走你的點擊，避免和它打架。
把模式切回去，簾幕就會收起來。

---

AkagiMS 出自 [Akagi](https://github.com/shinkuan/Akagi)，後者支援更多平台，
也能載入你自己的 bot 模型。
