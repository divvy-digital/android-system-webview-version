# android-system-webview-version

This repository provides a configuration json, used by the [Generate Android Launcher](https://github.com/divvy-digital/android-watchdog) version >= 0.0.42, to indicate what version of the WebView should be installed and where from to pull an installer APK.

## Downgrading

For testing, such as to test the WebView upgrade process on a device that has already beein upgrade, or possibly some unknown reason, it may be useful to be able to downgrade the WebView.

- Download android system webview apk file from [Apk Mirror](https://www.apkmirror.com/apk/google-inc/android-system-webview/android-system-webview-81-0-4044-138-release/android-system-webview-81-0-4044-138-2-android-apk-download/).
- Install using adb
    - `adb install -r -d com.google.android.webview_81.0.4044.138-404413800_minAPI21\(armeabi-v7a\)\(nodpi\)_apkmirror.com.apk`
