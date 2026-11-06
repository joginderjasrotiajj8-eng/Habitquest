# HabitQuest Android project

This repository wraps the original HabitQuest HTML/CSS/JavaScript app in Capacitor 7.

## GitHub build

1. Create a new GitHub repository named `HabitQuest`.
2. Extract this ZIP on your phone or computer.
3. Upload the **contents** of this folder to the repository root. Do not upload the ZIP itself.
4. Confirm that `www`, `.github`, `package.json`, and `capacitor.config.json` are visible at the repository root.
5. Open **Actions** and select **Build HabitQuest Android APK**.
6. Choose **Run workflow** if the push did not start it automatically.
7. Wait for the run to finish with a green check.
8. Open the successful run, scroll to **Artifacts**, and download **HabitQuest-APK**.
9. Extract the downloaded artifact ZIP. It contains `app-debug.apk`.

## Important

- This creates a debug APK for testing, not a Play Store release.
- Keep the original folder structure when uploading.
- If a build fails, open the failed job and share the **first red error line** plus the step name. A cancelled run is not enough information to diagnose a compiler error.
- The original app uses external CDN resources (Tailwind, Lucide, Tone.js, and Google Fonts), so those features may require an internet connection.
