# Tesh Real Pool — Android project

This is a starter Android Studio project containing a playable, landscape, 3D-style pool prototype in a WebView.

## Build an APK
1. Transfer this ZIP to a computer with Android Studio installed.
2. Extract the ZIP.
3. Open the `Realistic_Pool_Android_Project` folder in Android Studio.
4. Allow Gradle sync and install the required Android SDK (compile SDK 35).
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Find the debug APK at `app/build/outputs/apk/debug/app-debug.apk`.

## Prototype limits
- This is not a compiled APK yet; this ZIP contains source project files.
- The table is a 2D-rendered perspective/3D-style prototype, not a full 3D physics engine.
- The game has basic collisions, aiming, power and local pass-and-play turns.
- Bluetooth/hotspot multiplayer, online multiplayer, advanced spin, full official rule enforcement and genuine 3D rendering are not implemented yet.

## Build APK online using only your phone
This project includes a GitHub Actions workflow at `.github/workflows/android.yml`.
1. Create/sign in to a GitHub account in your phone browser.
2. Create a new repository and upload the extracted project files, keeping the `.github/workflows/android.yml` path.
3. Open the repository's Actions tab and run **Build Tesh Real Pool APK** (or wait for the push build).
4. Open the completed workflow run and download the `Tesh-Real-Pool-debug-apk` artifact.
5. Extract the downloaded artifact ZIP to get `app-debug.apk`, then tap it to install. You may need to allow installs from your browser/files app.
This workflow produces a debug APK, not a Play Store release. Android may show a warning because it is not Play Store-signed.
