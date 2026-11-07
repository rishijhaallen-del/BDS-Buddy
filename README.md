# BDS Buddy

Android attendance tracker for individual lectures and practicals.

## Cloud APK build (phone-friendly)

This project includes a GitHub Actions workflow at `.github/workflows/android.yml`.

1. Create a GitHub repository named `BDS-Buddy`.
2. Upload the contents of this project (including the hidden `.github` folder) to the repository's `main` branch.
3. Open the repository's **Actions** tab and select **Build BDS Buddy APK**.
4. Tap **Run workflow**. The workflow uses Java 17 and Gradle 8.7, then uploads `app-debug.apk` as an artifact.
5. When the run succeeds, open the run and download the `BDS-Buddy-debug-APK` artifact. Extract the ZIP and install `app-debug.apk` on your Android phone.

The app stores attendance locally on the device. Uninstalling the app or clearing its data can remove that attendance history.
