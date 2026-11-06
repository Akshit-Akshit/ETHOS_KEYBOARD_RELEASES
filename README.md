# ETHOS_KEYBOARD Releases

Official public distribution repository for **ETHOS_KEYBOARD** compiled Android application packages (APK).

---

## About ETHOS_KEYBOARD

**ETHOS_KEYBOARD** turns an Android smartphone into a standard wireless Bluetooth Classic HID (Human Interface Device) keyboard.

- **No Root Required**: Built entirely on native Android public APIs.
- **No PC-Side Receiver Software**: Your PC or laptop recognizes your phone as a genuine physical Bluetooth keyboard.
- **Zero Drivers / Daemons**: Works out of the box on Linux (BlueZ) and Windows 11.
- **High-Speed Typing**: Configurable typing speed from 1 up to 50 characters per second (CPS).
- **Code & Text Streaming**: Supports ordinary text as well as programming code (C++, Java, Python, SQL, HTML/CSS).
- **Interactive Controls**: Live Start, Pause, Resume, and Stop controls with automatic safety key release.

---

## Download Latest APK

Download the signed release APK from the **GitHub Releases** section:

👉 **[Download Latest Release](https://github.com/Akshit-Akshit/ETHOS_KEYBOARD_RELEASES/releases/latest)**

Each release includes:
1. `ETHOS_KEYBOARD.apk` — The production-signed, installable Android application.
2. `SHA256SUMS.txt` — SHA-256 cryptographic checksum for verifying package integrity.

---

## Installation & Setup Guide

### 1. Installation
1. Download `ETHOS_KEYBOARD.apk` on your Android device (Android 9.0+ / API 28+).
2. If prompted by Android, allow installation from your browser/file manager ("Install unknown apps").
3. Tap **Install** and open **Bluetooth Keyboard**.

### 2. Pairing with your Computer
1. On your phone, tap **DETECT HID PROFILE**.
2. Tap **REGISTER AS KEYBOARD**.
3. Tap **MAKE PHONE DISCOVERABLE**.
4. On your PC (Linux or Windows 11):
   - Open Bluetooth settings and search for your phone.
   - Pair and confirm the passkey on both devices.
5. In the app, select your PC from the paired hosts dropdown and tap **CONNECT TO HOST**.

### 3. Typing / Code Injection
1. Paste or type text/code into the built-in editor.
2. Adjust the typing speed slider (1 to 50 CPS).
3. Place your cursor in any text editor, IDE (VS Code, Notepad, terminal), or browser on your computer.
4. Tap **START** on your phone.

---

## Security & Verification

All official APK releases are signed with the developer's dedicated production key.

To verify the checksum on Linux / macOS:
```bash
sha256sum -c SHA256SUMS.txt
```
Or on Windows PowerShell:
```powershell
Get-FileHash .\ETHOS_KEYBOARD.apk -Algorithm SHA256
```

---

## Issues & Feedback

If you encounter any issues or have feature requests, please submit an issue via the [GitHub Issue Tracker](https://github.com/Akshit-Akshit/ETHOS_KEYBOARD_RELEASES/issues).
