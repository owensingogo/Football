# Touchline Legacy — Offline Android football management prototype

A lightweight, offline-first prototype for Android (including Tecno phones). It is a native Android project using Kotlin + Jetpack Compose. It includes:
- Create a manager profile and choose a coaching style
- Browse job vacancies and apply for jobs
- Accept a club job and enter a simple career dashboard
- Simulate a match result and update points, manager reputation, news and history
- Simulated in-game social posts and press Q&A
- Local save using Android SharedPreferences (JSON), no internet permission or account needed

## Requirements
- Android Studio (recent stable version)
- Android SDK 35 installed
- JDK 17 (Android Studio bundled JDK is fine)
- Android phone running Android 8.0 (API 26) or newer

## Open and build
1. Extract this ZIP.
2. Open the `TouchlineLegacy` folder in Android Studio.
3. Wait for Gradle sync. If prompted, install Android SDK Platform 35 and Build Tools.
4. Connect the Tecno phone with USB debugging enabled, or use an Android emulator.
5. Press **Run** to install and launch.
6. To make an APK: **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
7. The debug APK will normally be at `app/build/outputs/apk/debug/app-debug.apk`.
8. To install manually, copy that APK to the phone and open it. Android may ask you to allow installation from that file manager.

## Important
- This is a playable starter prototype, not a finished commercial game.
- The starter uses fictional clubs and players so it can be distributed safely without bundled unlicensed databases, club crests or player likenesses. Add a properly licensed database later.
- The social feed and news are simulated and work offline; they do not post to real Facebook.
- Match results are a simple prototype simulation, not a full tactical match engine.
- The project requires Gradle to download Android build dependencies once. After the first successful sync/build, gameplay itself works offline.
