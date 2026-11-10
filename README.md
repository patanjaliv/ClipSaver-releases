# ClipSaver for Android

Saves videos from Instagram, Facebook, X/Twitter, Threads and YouTube straight into
your phone's Gallery. Everything runs on the phone; no account, no server, no ads.

This repository holds only the installable APK files. The source code lives in a
private repository.

## Download

**Latest version:** <https://github.com/patanjaliv/ClipSaver-releases/releases/latest/download/ClipSaver.apk>

Works on any 64-bit Android phone running Android 10 or newer.

## Install (about 2 minutes, no computer needed)

1. Open the link above on the phone. The file `ClipSaver.apk` goes to **Downloads**.
2. Open the **Files** app, go to Downloads, tap `ClipSaver.apk`.
3. The phone warns it cannot install unknown apps from this source. Tap **Settings**,
   switch on **Allow from this source**, go back.
4. Tap **Install**. If Google Play Protect asks, tap **Install anyway** (the app is not
   on the Play Store, so Google has never seen it; that is all the warning means).
5. Open ClipSaver once so it finishes setting up.

## Use

- In Instagram, Facebook, X, Threads or YouTube tap **Share**, then **ClipSaver**.
  The video lands in Gallery under **ClipSaver**.
- Updating later: install the new `ClipSaver.apk` over the old one the same way.
  Settings and logins are kept.

## Verify a download (optional)

Every release lists the SHA-256 of its APK. On a computer:

```
shasum -a 256 ClipSaver.apk        # macOS / Linux
certutil -hashfile ClipSaver.apk SHA256   # Windows
```
