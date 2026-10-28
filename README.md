# CineMax Fire TV

A lightweight Android / Fire TV wrapper for the existing CineMax web app:

https://cinemax.floot.app

## What it does

- Opens CineMax full-screen.
- Supports Fire TV / Android TV remote navigation through the web app's D-pad handling.
- Uses landscape orientation.
- Allows media playback without requiring an extra touch gesture.
- Produces a normal sideloadable APK.
- Does not require publishing to Google Play or the Amazon Appstore.

## Build in GitHub

1. Create a GitHub repository.
2. Upload all files from this project, preserving the folder structure.
3. Open **Actions** → **Build CineMax Fire TV APK**.
4. Choose **Run workflow**.
5. After it succeeds, open the run and download the `CineMax-FireTV-APK` artifact.
6. Unzip it to get `app-release.apk`.
7. Sideload that APK onto the Fire Stick.

The release build is signed with Android's generated debug signing configuration. It is suitable for private sideloading, not public store distribution.
