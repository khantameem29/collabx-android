# CollabX — Android App

Android app for **CollabX**, my student project collaboration platform (Kanban boards, real-time chat, file sharing). A lightweight WebView wrapper that opens the live web app full-screen, so it can be installed and used like a native app.

**Web app:** https://frontend-iota-liart-82.vercel.app
**Download APK:** [`apk/CollabX.apk`](apk/CollabX.apk)

## Features

- Full-screen app experience with themed status and navigation bars
- Hardware back button navigates inside the app
- File uploads supported
- Friendly offline screen with a retry button
- Minimum Android 7.0 (API 24)

## Install

Download the APK on an Android phone, open it, and allow "Install unknown apps" when prompted. Requires an internet connection (the app loads the live site).

## Build from source

Plain Java + Android SDK command-line tools, no Gradle:

```bash
KS=release.keystore KS_PASS=yourpass KS_ALIAS=youralias ./build.sh
```

---
Tameem Khan · [Portfolio](https://khantameem29.github.io) · [GitHub](https://github.com/khantameem29) · ktameem2004@gmail.com
