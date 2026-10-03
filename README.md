
# Void Equalizer

Mobile-friendly Android equalizer project.

## Build online with GitHub Actions

1. Upload this project to a GitHub repository.
2. GitHub Actions will build on push to `main`.
3. Open **Actions** -> **Build Void Equalizer APK**.
4. Download the `Void-Equalizer-debug` artifact.

## Notes

The 800% control is an app-level gain target. Android/device audio hardware may cap actual output volume. Excessive gain can clip or distort audio.

The battery optimization request is shown at first launch. Android requires the user to approve unrestricted battery usage; an app cannot silently grant this permission.
