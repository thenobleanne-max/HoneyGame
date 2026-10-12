# HoneyGame Android APK project

This project packages the HoneyGame HTML game into an Android app and builds a debug APK using GitHub Actions.

## Build the APK (no Lovable credits required)

1. On your phone or computer, sign in to GitHub and create a **new repository** named `HoneyGame`. Keep it private if you prefer.
2. Upload the contents of this ZIP into the repository. Make sure the repository root contains `config.xml`, the `www` folder, and `.github/workflows/build-apk.yml`.
3. Open the repository's **Actions** tab. If prompted, enable Actions.
4. Select **Build HoneyGame Android APK** on the left, then tap **Run workflow**. If you don't see it, first commit/push the files to the `main` branch.
5. Wait for the workflow to finish with a green check mark.
6. Open that successful run, scroll to **Artifacts**, and download `HoneyGame-Android-APK`. Extract the downloaded ZIP to get `app-debug.apk`.
7. Transfer/open `app-debug.apk` on your Android phone. If Android asks, allow your browser or file manager to install unknown apps, then install HoneyGame.

## Notes
- This creates a **debug APK** for personal installation, not a Play Store release.
- Keep your GitHub repository private if you don't want the game source public.
- Android may show a safety warning because this is a self-built APK. Only install APKs you built and trust.
- The app uses the current HoneyGame HTML game as its offline main screen.
