UZHAVAN HOTEL BILLING - ANDROID SOURCE PROJECT

Included:
- Existing updated HTML app bundled inside Android WebView
- Menu item photo picker (device gallery/file picker)
- Date-wise report and overall report present in bundled HTML
- Gradle Android project files
- GitHub Actions workflow to build a debug APK

IMPORTANT:
This is Android source code, not an already compiled APK. It has not been built/tested on a real phone in this environment. Before using it for actual business, test billing, image upload, report calculations, and backup/restore with sample data. Browser/WebView local storage is local to this app installation; export backups regularly.

BUILD APK USING GITHUB (phone-friendly):
1. Download and extract this ZIP.
2. Open github.com and create a NEW repository (for example: uzhavan-hotel-billing). Do not upload private customer/billing data.
3. Upload all extracted project files and folders to the repository root, preserving folder structure. Ensure .github/workflows/build-apk.yml is included. If using GitHub website, upload the files/folders from a computer if folder upload on mobile is inconvenient.
4. Open repository -> Actions -> “Build Uzhavan APK” -> Run workflow.
5. Wait for the workflow to finish successfully.
6. Open the completed workflow run, scroll to Artifacts, and download Uzhavan-Hotel-Billing-debug-apk.
7. Extract the downloaded artifact ZIP; it contains app-debug.apk. Transfer it to the Android phone and install it. Android may ask to allow installs from that browser/file manager.

ALTERNATIVE: Open this project in Android Studio with Android SDK 35 and Java 17, then run: gradle assembleDebug

App ID: com.uzhavan.hotelbilling
Version: 1.1
