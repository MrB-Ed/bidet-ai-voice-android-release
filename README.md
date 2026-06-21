# Bidet AI Voice for Android

Bidet AI Voice is the native Android lane for Bidet AI: fast floating-mic dictation plus long-form Walk-and-Talk recording that can keep capturing with the screen off.

This repository is a public release-asset lane for trusted testers and builder-preview downloads. The full Android source lane is still being scrubbed and prepared separately.

## Current Release

- Version: `0.1.0`
- APK: `bidet-voice-RELEASE-0.1.0.apk`
- Size: 39.5 MB
- SHA-256: `8D0F299C50671ED0029CD688A5EBC118BE68C14AEAEB43F51EDF8B87FE81103E`
- Tested device lane: Pixel 8 Pro
- Minimum Android: Android 12 / API 31

## What It Does

- Floating mic overlay for fast voice insertion into Android text fields.
- Cloud STT path using the user's own Groq key.
- Optional cleanup path using the user's own cleanup key.
- Native Walk-and-Talk recording through a foreground service, with screen-off support.
- Editable transcript output with Copy, Share, and Save actions.
- On-device STT path exists, but fresh sideload installs need the local model setup or cloud-key fallback.

## Install Shape

1. Download the APK from the latest release.
2. Allow install from this source on Android.
3. Grant microphone and notification permissions.
4. Enable the Bidet AI Voice Accessibility service.
5. Add your own API keys for cloud dictation and cleanup.

## Honest Boundary

This is not the Play Store build yet. It is a signed sideload preview for people comfortable with Android permissions, Accessibility services, and builder-preview software.

Play Store packaging, public support docs, source publication, and a smoother model-install path are roadmap items.
