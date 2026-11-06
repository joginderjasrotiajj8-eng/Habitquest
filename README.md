# HabitQuest Android APK

This repository builds the HabitQuest HTML app into an installable Android debug APK using GitHub Actions.

## Upload to GitHub

1. Create a new GitHub repository.
2. Extract this ZIP on your phone or computer.
3. Upload the **contents** of this folder to the repository root. Do not upload the outer ZIP.
4. Keep the folder structure exactly as shown:
   - `.github/workflows/android-apk.yml`
   - `www/index.html`
   - `package.json`
   - `capacitor.config.json`

## Build

1. Open the repository's **Actions** tab.
2. Choose **Build HabitQuest Android APK**.
3. Tap **Run workflow** and confirm.
4. Wait for the run to finish with a green check mark.
5. Open that successful run's **Summary** page.
6. Find **Artifacts** and download **HabitQuest-Android-APK**.
7. Extract the downloaded ZIP. The file inside is `app-debug.apk`.

## Important

- Artifacts are created only after a successful workflow run.
- The APK is a debug build for testing and personal installation, not a Play Store release.
- The app may need an internet connection for any external fonts, libraries, or services loaded by the original HTML.
