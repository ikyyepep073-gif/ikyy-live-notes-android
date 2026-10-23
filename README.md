# IKYY Live Notes Android APK project

This Android WebView app opens the existing IKYY Live Notes website and adds a black/blue gaming header.

## Build on GitHub (phone-friendly)
1. Create a new public or private GitHub repository, e.g. `ikyy-live-notes-android`.
2. Upload all files and folders in this project to the repository root (including `.github/workflows/build-apk.yml`).
3. Open the repository's **Actions** tab.
4. Select **Build IKYY Live Notes APK** and tap **Run workflow** (or push to `main`).
5. When the run completes, open it and download the `IKYY-Live-Notes-APK` artifact. Extract the ZIP to get `app-debug.apk`.
6. Open the APK on Android to install it. You may need to allow installing unknown apps for the browser/files app.

This is a debug APK, not a Play Store release. The app loads the website online; it does not work offline. The admin panel must first be implemented correctly in the website itself.
