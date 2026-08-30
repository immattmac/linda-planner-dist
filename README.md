# Linda Planner — distribution

Public distribution channel for the private **Linda Planner** household app. Holds only the
built APK (as GitHub Releases) and `version.json`, which the app reads to offer in-app
updates. No source code lives here — that's in the private `linda-planner` repo.

- `version.json` — latest `versionCode` / `versionName` + the APK URL the app checks.
- Latest APK: https://github.com/immattmac/linda-planner-dist/releases/latest/download/app-release.apk

The APK contains no secrets (the FCM service-account key is imported on each phone at
runtime and is never bundled).
