# 🛰️ TMP admin-detector

![Product Name](https://img.shields.io/badge/Product-admin--detector-EF4444?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.0.3-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows)

**admin-detector** is a lightweight utility designed for TruckersMP players. It monitors and alerts you in real-time when a staff member spawns within your rendering proximity.

---

## ✨ Features

*   **Real-Time Detection:** Instantly scans and identifies staff members.
*   **Non-Focus Popups:** Notifications that appear in the bottom right of your screen without stealing focus from your game inputs.
*   **Staff Role Integration:** Identifies not just the name, but also the specific role (e.g., Game Moderator, Support, Manager).
*   **Auto-Updater:** The app automatically checks for new versions and installs them, so you never miss an update.

---

## 🛠️ Requirements & Setup

For this application to function, it must be able to read your spawning data. **You must enable advanced logging within the TruckersMP client.**

### 1. Enable Developer Logging
1.  Open TruckersMP tab menu and go to **Settings**.
2.  Navigate to the **General** tab.
3.  Where it says "Development Logging", it must be set to **"ADVANCED"**.
4.  The game automatically starts logging. Just restart the Admin Detector if it was already running.

> [!IMPORTANT]
> Without "Developer logging" enabled, TruckersMP will not write spawn data to your local files, and the detector will not work.

**Refer to the image below for the exact setting location:**

![TruckersMP Settings](https://i.postimg.cc/Z5N3tRJc/image-2026-07-10-135032965.png)

### 2. Installation
1.  Navigate to the [Latest Release](https://github.com/GraylineLabs/TruckersMP-Admin-Detector/releases/latest).
2.  Download `admin-detector-setup.exe`.
3.  Run the installer and follow the on-screen prompts.
4.  Launch the application and ensure the status shows **"SYSTEM LIVE"**.

---

## 🖥️ Preview

The application features a modern, dark-themed dashboard that keeps a history of all detections during your current session:

*   **Dashboard:** Displays name, role, ID, and exact time of detection.
*   **Alerts:** High-contrast red popups with a distinct "ping" audio notification.
*   ![Popup Notification](https://i.postimg.cc/154nZKGQ/gunner.png)

---

## 🔒 Privacy & Security

*   **Local Processing:** All log scanning happens locally on your machine. The only external calls are fetching the staff list, and updating the application.
*   **Authenticated Sync:** Staff lists are frequently updated with new team additions and the application automatically fetches these from a private repository.
*   **No Game Injection:** This app does **not** inject code into ETS2/ATS or TruckersMP, making it safe to use alongside the client without breaking TruckersMP terms of service. (This is not fact checked with TruckersMP, so use with caution to be sure).

---

## 🤝 Credits

Developed and Maintained by **GrayLineLabs**.  

---
*Disclaimer: This tool is not affiliated with or endorsed by TruckersMP.*
