# IWD Web APK

A minimal Android WebView application that embeds `https://iwd.illusd.com/` as an installable APK.

## Download the APK

Every push and pull request runs the **Build APK** GitHub Actions workflow. Open the workflow run and download the `iwd-debug-apk` artifact; it contains `app-debug.apk`.

## Build locally

```bash
gradle assembleDebug
```

The debug APK is generated at `app/build/outputs/apk/debug/app-debug.apk`.
