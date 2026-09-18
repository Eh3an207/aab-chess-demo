# aab-chess-demo
A fully functional Android Chess application, built end-to-end on a smartphone using AAB (Android AI Bridge) via Termux — no desktop, no Android Studio required.

# ♟️ AAB Chess Demo

A fully functional Android Chess application, built end-to-end **on a smartphone** using **AAB (Android AI Bridge)** via Termux — no desktop, no Android Studio.

## 📥 Download & Install
1. Go to the [Releases](https://github.com/Eh3an207/aab-chess-demo/releases) section
2. Download the APK
3. Install it (allow "Install from unknown sources" if prompted)

## ⚙️ How It Was Built
- **Environment:** Termux (ARM64) directly on an Android phone
- **Build System:** Gradle + Android SDK orchestrated by AAB
- **No desktop or IDE was used** in the entire build cycle.

## 🧠 The Engineering Challenge
Running a full Gradle build pipeline on a mobile ARM64 environment — dependency resolution, memory constraints, and build stability — was the real test. The result: a signed, production-grade APK built entirely on-device.
