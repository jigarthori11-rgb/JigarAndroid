# Jigar Android Launcher

A basic Android Studio Kotlin project that opens the supplied $GrandV launcher in an immersive landscape WebView.

## Build
1. Install Android Studio (latest stable) on a computer.
2. Open this `JigarAndroid` folder in Android Studio.
3. Let Gradle sync and install Android SDK Platform 35 if prompted.
4. Use **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Android Studio will show the generated APK location.

## Important compatibility note
The website itself says it expects an up-to-date Chromium browser. This app uses Android System WebView, which may not expose all Chromium/WebGPU features needed by the game. The launcher may open while the actual game fails to initialize. For best compatibility, use the latest Chrome on Android to test the original website. This wrapper does not include GTA V game files and does not bypass the site's LAN certificate or device requirements.
