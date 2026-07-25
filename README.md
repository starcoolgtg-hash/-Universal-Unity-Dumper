# 🚀 STARCOOL DUMPER

![Release](https://img.shields.io/badge/Release-v3.0.1-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Android%2010%2B-blue)
![Architecture](https://img.shields.io/badge/Arch-arm64--v8a-orange)
![Android 15](https://img.shields.io/badge/Android%2015-Compatible-red)

**STARCOOL DUMPER** is a professional-grade Android toolkit designed for high-end ELF analysis and Unity/IL2CPP reverse engineering. By combining a high-performance **Rust engine** with an advanced **C++ live injection system**, it provides the most stable and detailed dumping experience available for modern Android devices.

---

## ✨ Key Features

### 🛠️ Dual-Engine Analysis
*   **Static Engine (Rust-Powered):** Performs ultra-fast ELF parsing and symbol extraction from raw `.so` files without requiring Root or a running process.
*   **Live Engine (C++ Backend):** Real-time process injection using the **Dobby Hooking** framework to dump metadata directly from the game's active memory.

### 🎯 Unity/IL2CPP Specialized
*   **Rich Metadata Output:** Automatically generates `dump.cs`, `il2cpp.h`, `script.json` (for IDA Pro), and `script.py`.
*   **Advanced Reconstruction:** Recovers class structures, namespaces, method offsets, and static fields.
*   **Auto-Collect System:** Automatically detects and moves dump files from the game's internal directory to public storage (`/sdcard/Dumper/`).

### 🛡️ Android 15 & 16KB Optimized
*   **Modern Compatibility:** Fully optimized for the latest Android 15 devices.
*   **16KB Page Alignment:** Built using the latest NDK standards to ensure injected libraries are valid on flagship hardware (Pixel, Infinix, etc.).

### 🖥️ Integrated Live Terminal
*   **Real-time Monitoring:** Watch the injection and dumping process line-by-line via the built-in terminal dashboard.
*   **Multi-Tag Logging:** Integrated logs from `MXP`, `StarcoolRuntime`, and `Root Shell`.

---

## 🌍 Global Language Support
The interface is fully localized and automatically synchronizes with your device language. Currently supporting:
*   🇺🇸 **English** (Standard)
*   🇮🇩 **Indonesian**
*   🇸🇦 **Arabic**
*   🇫🇷 **French**
*   🇷🇺 **Russian**
*   *...and 5 other major languages.*

---

## 🏗️ Technical Stack
*   **Frontend:** Kotlin & Jetpack Compose (Modern, Lightweight UI)
*   **Static Analysis:** Rust (Memory safety and speed)
*   **Live Backend:** C++ 20 (Direct memory access)
*   **Hooking Framework:** Dobby
*   **Memory Management:** KittyMemory

---

## 🚀 How to Use

### Mode 1: Static Analysis
1.  Open the app and select **"Select Library"**.
2.  Choose a `.so` file from your device storage.
3.  Configure your extraction settings (Symbols, Strings, Reconstruction).
4.  Click **"Generate Dump"**.

### Mode 2: Unity Dumper (Root Required)
1.  Enter the **Game Package Name** in the Unity Dumper card.
2.  Click **"Inject & Dump Now"**.
3.  The app will automatically launch the target game.
4.  Confirm the injection when the game reaches the Lobby or Match.
5.  Monitor the **Terminal** and find your files in the `/Dumper/` folder.

---

## 🤝 Connect with Us
Join our community for updates, support, and technical discussions:
*   📢 **Telegram Channel:** [STARCOOL PLUS](https://t.me/STARCOOLPLUS)
*   💬 **Discussion Group:** [Join Chat](https://t.me/+pvVFT5Dfcvk2MzM1)

---

## 📜 Disclaimer
This tool is intended for educational and research purposes only. The developer is not responsible for any misuse or damage caused by this application. Always respect the Terms of Service of the software you are analyzing.

---
*Developed by STARCOOL | v3.0.1 Professional Edition*
