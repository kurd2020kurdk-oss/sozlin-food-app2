# GitHub / Cloud Build

This repository includes `.github/workflows/build-apk.yml`.

After uploading the project to GitHub:

1. Open the repository on GitHub.
2. Go to **Actions**.
3. Select **Build Android APK**.
4. Choose **Run workflow** (or push to `main`/`master`).
5. Wait for the workflow to finish.
6. Open the completed workflow run.
7. Under **Artifacts**, download `sozlin-food-app-release-apk`.
8. Unzip the artifact and install `app-release.apk` on an Android phone.

The workflow installs Flutter and Java, regenerates the Android platform files, runs `flutter pub get`, runs `flutter analyze`, builds a release APK, and uploads the APK as a GitHub Actions artifact.
