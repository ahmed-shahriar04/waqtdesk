<div align="center">

  <img src="WaqtDesk/@Resources/Images/app_icon.png" alt="WaqtDesk Logo" width="115" />

  # 🌙 WaqtDesk

  ### Next-Gen Glassmorphic Desktop Prayer Times Widget for Windows
  *Engineered for precision, fluid aesthetics, and distraction-free daily workflow.*

  <p align="center">
    <a href="https://github.com/ShahriarAhmedRiaz/WaqtDesk/releases">
      <img src="https://img.shields.io/badge/Release-v3.5.0-2dd4bf?style=for-the-badge&logo=windows&logoColor=white" alt="Version 3.5.0" />
    </a>
    <a href="https://codiology.vercel.app">
      <img src="https://img.shields.io/badge/Powered%20By-Codiology%20Labs-0f172a?style=for-the-badge&logo=vercel&logoColor=white" alt="Codiology Labs" />
    </a>
    <a href="LICENSE">
      <img src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-ff4757?style=for-the-badge" alt="CC BY-NC 4.0" />
    </a>
  </p>

  <p align="center">
    <a href="#-overview">Overview</a> •
    <a href="#-features">Features</a> •
    <a href="#-visual-tour">Visual Tour</a> •
    <a href="#-installation">Installation</a> •
    <a href="#-settings--customization">Settings</a> •
    <a href="#-license--terms">License</a> •
    <a href="#-credits">Credits</a>
  </p>

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0f2927&height=80&section=header" width="100%" />

</div>

---

## ⚡ Overview

**WaqtDesk** is a modern, glassmorphic desktop prayer HUD built on Rainmeter and driven by a high-performance event-driven Lua engine. It provides an unobtrusive, distraction-free companion on your desktop—tracking prayer schedules down to the second, updating dynamic celestial bodies in real time, and presenting essential daily solar metrics at a glance.

---

## ✨ Features

- 🌌 **Unified Glassmorphic UI:** Deep emerald frosted-glass design tailored to blend naturally with modern Windows 11 dark workspaces.
- ⏱️ **Second-by-Second Countdown:** Live countdown display with neon accent highlights on the currently active prayer window.
- ☀️ **Dynamic Celestial Viewport:** Real-time orbital movement of the Sun and Moon, shifting coordinates smoothly throughout the day.
- 🎛️ **2×2 Solar Glance Chips:** Compact, glanceable metric badges for Sunrise, Sunset, Sahri end time, and Iftar.
- ⚙️ **On-Widget Settings Suite:** Access the configuration dashboard right from the top-right gear icon (⚙):
  - **Madhab Switcher:** Instant toggle between **Hanafi** (2× shadow rule) and **Shafi'i / General** (1× shadow rule).
  - **Bilingual Interface:** Real-time one-click translation between **English** and **বাংলা (Bengali)**.
  - **Smart Geolocation:** Automatic IP-based location detection with support for custom manual coordinates.
- 🛡️ **Zero Resource Overhead:** Near-zero CPU impact and optimized memory handling via event-driven Lua execution.

---

## 📸 Visual Tour

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <b>Compact Desktop HUD</b><br/>
        <i>Minimal floating workspace glance</i>
      </td>
      <td align="center" width="50%">
        <b>Expanded Detail Panel</b><br/>
        <i>Clean 5-prayer timetable with active glow tiles</i>
      </td>
    </tr>
  </table>
</div>

---

## 📥 Installation

### Prerequisites
1. Download and install **[Rainmeter 4.5 or newer](https://www.rainmeter.net/)**.
2. If using the Bengali language mode, ensure a suitable Bengali font (such as *Kalpurush*, *Hind Siliguri*, or *SolaimanLipi*) is installed on Windows.

### Setup Instructions
```bash
# Clone the repository directly into your Rainmeter skins directory
git clone [https://github.com/ShahriarAhmedRiaz/WaqtDesk.git](https://github.com/ShahriarAhmedRiaz/WaqtDesk.git) "%USERPROFILE%\Documents\Rainmeter\Skins\WaqtDesk"

```

1. Open your system tray, right-click the **Rainmeter** icon, and select **Refresh all**.
2. In the Rainmeter Manager window, expand the `WaqtDesk` folder and select `WaqtDesk.ini`.
3. Click the **Load** button in the top-right corner.

---

## ⚙️ Settings & Customization

Click the **⚙** gear icon located in the expanded panel's top-right corner to open the preference suite:

| Parameter | Options | Description |
| --- | --- | --- |
| **School (Madhab)** | `Hanafi` / `Shafi'i` | Toggles the Asr prayer calculation method between Hanafi and Standard. |
| **Language** | `English` / `বাংলা` | Translates all interface labels, timetable names, and dates instantly. |
| **Location** | `Auto IP` / `Manual` | Uses automatic IP lookup or allows custom Latitude and Longitude input. |

---

## 🔒 License & Terms

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.

* ✅ **Free for Personal Use:** You are free to download, use, and modify the skin for personal purposes.
* ❌ **Commercial Use Prohibited:** You may not sell, monetize, redistribute for commercial gain, or bundle this software into paid products.
* 🏷️ **Attribution Required:** Any public fork or redistribution must retain clear attribution to **Shahriar Ahmed Riaz** and **Codiology Labs**.

---

## 👨‍💻 Credits & Maintainers

# Shahriar Ahmed Riaz
# Codiology Labs

---
