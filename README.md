# Juhudi Educational Hub

This starter project wraps the existing Google Sites website in an Android app using Capacitor.

## Build the APK without installing Android Studio

1. Create a free GitHub account and a new repository named `juhudi-educational-hub`.
2. Upload all files and folders from this project to the repository (keep `.github/workflows/build-apk.yml`).
3. Open the repository's **Actions** tab.
4. Select **Build Juhudi Android APK**, then choose **Run workflow**.
5. When the workflow finishes successfully, open its run and download the artifact named **Juhudi-Educational-Hub-APK**.
6. Extract the downloaded ZIP. The APK inside is `app-debug.apk`.

## Important

- The app needs an internet connection because the learning content is hosted on Google Sites.
- This first version opens the existing site; it does not redesign or copy Google Sites content.
- The APK produced by this workflow is a debug APK for testing and direct installation. A signed release APK is a separate publishing step.
- Keep the app ID `com.jovinbrayson.juhudieducationalhub` stable after publishing.
