# SNOWORA Android Releases

Official Android APK releases and updates for **SNOWORA** — your essential skiing companion.

SNOWORA's development source code is maintained privately. This public repository
is used only to distribute signed Android APKs and release metadata. No account
or GitHub sign-in is required to download the APK.

## Download the latest stable Android version

**[Download SNOWORA.apk](https://github.com/instbaeck-ship-it/SNOWORA-RELEASES/releases/latest/download/SNOWORA.apk)**

The link stays the same when a newer stable version is published. The link
becomes active after the **first** release is published.

- [Release notes and previous versions](https://github.com/instbaeck-ship-it/SNOWORA-RELEASES/releases)
- [Latest version metadata (update.json)](https://github.com/instbaeck-ship-it/SNOWORA-RELEASES/releases/latest/download/update.json)

### Installing and updating

1. On Android, download the APK from the latest link above.
2. If prompted, allow APK installation **for the browser that downloaded it**.
3. Review Android's installation confirmation before proceeding.
4. To update, install a newer signed APK **without uninstalling** SNOWORA.
   The original signing certificate must match for Android to allow this.

SNOWORA also checks the latest stable release from inside the app and offers
an update link when a newer Android `versionCode` is available. Android does not
permit background silent APK installation through this process.

Only download APKs from this official repository's Releases page. Inspect the
release's `update.json` for the APK SHA-256 checksum and build version.

> Note: APKs are not yet available until the first signed stable release
> successfully completes verification and is published.
