# Privacy Policy — Needledeck

**Effective date:** 21 October 2026
**App:** Needledeck (Android) — package `com.krissirk.needledeck`

## The short version

Needledeck is an offline music player. It has no accounts, no ads, no analytics
and no profiling. Your music library never leaves your device. The only data
that ever leaves your device is anonymous crash diagnostics.

## What Needledeck reads

Needledeck reads the audio files already stored on your device through Android's
MediaStore:

- Song titles, artists, albums, durations and file sizes
- Embedded album artwork
- The audio itself, in order to play it

This data is read **on your device**. It is never uploaded, never indexed on a
server, and never shared with anyone.

## Permissions and why we ask

| Permission | Why |
|---|---|
| `READ_MEDIA_AUDIO` (Android 13+) / `READ_EXTERNAL_STORAGE` (Android 12 and below) | To list and play the audio files on your device |
| `POST_NOTIFICATIONS` | To show playback controls in the notification shade |
| `FOREGROUND_SERVICE` + `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | To keep playing when the app is in the background |
| `WAKE_LOCK` | To stop the screen sleeping during playback |
| `INTERNET` | **Only** to send anonymous crash reports. The app makes no other network requests |

You can revoke the audio permission at any time in Android Settings. Needledeck
will show an empty library and nothing else.

## What is stored on your device

Favourites and playlists are saved in the app's private storage
(`SharedPreferences`). They are never transmitted. Uninstalling the app deletes
them permanently.

## What is sent to us

If the app crashes, Firebase Crashlytics sends an anonymous crash report
containing the error and the stack trace. It does **not** contain your music
library, your playlists, your favourites, or any personal identifier.

Crash reports are used only to fix bugs. We do not use them for profiling or
advertising.

## What we never do

- No account, no login, no email address required
- No advertising or ad SDKs
- No analytics, tracking, or fingerprinting
- No selling or sharing of data with third parties
- No background location, camera, microphone, contacts, or phone access

## Children

Needledeck is not directed at children under 13 and collects no personal
information from anyone.

## Changes

If this policy changes, the updated version will be published at this URL and
the effective date above will change. The app itself requires no account and
stores no remote profile, so a policy change cannot retroactively affect data
already on your device.

## Contact

Questions or requests: **<insert your contact email>**

If you want the data on your device removed, uninstalling Needledeck removes
it. For anything else, email the address above.
