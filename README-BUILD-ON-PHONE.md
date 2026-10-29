# Build the OneRoute Delivery APK using GitHub on your phone

This is a starter app, not a finished production app. The workflow builds a debug APK from the current source code. It does not implement automatic Swiggy/Zomato order syncing or full multi-stop route optimization.

## Steps
1. Extract this ZIP on your phone.
2. In your GitHub repository, upload the CONTENTS of the `OneRouteDelivery` folder to the repository root. Include the hidden `.github` folder and its `workflows/build-apk.yml` file. Do not upload only the ZIP.
3. Open the repository's **Actions** tab and select **Build OneRoute Delivery APK**.
4. Tap **Run workflow** if it has not started automatically.
5. Open the completed workflow run and download the artifact named `OneRouteDelivery-debug-apk`.
6. Extract the downloaded artifact ZIP, then tap `app-debug.apk` to install. Android may ask you to allow installs from that browser/file manager.

The APK is a debug build for testing, not a signed Play Store release.
