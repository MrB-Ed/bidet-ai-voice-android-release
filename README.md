# Bidet AI Voice for Android

Bidet AI Voice is the native Android lane for Bidet AI: fast floating-mic dictation plus long-form Walk-and-Talk recording that can keep capturing with the screen off.

This repository is a release-asset lane for trusted testers and builder-preview downloads. The full Android source lane is still being scrubbed and prepared separately.

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

1. Request tester access before downloading the APK.
2. Confirm the APK SHA-256 before installing.
3. Allow install from this source on Android.
4. Grant microphone and notification permissions.
5. Enable the Bidet AI Voice Accessibility service only if you understand the insertion workflow.
6. Add your own API keys for cloud dictation and cleanup.

## Tester Disclosure

- This is not a Play Store build.
- Android may show an unknown-source install warning.
- The Accessibility service is used for supported text insertion workflows. Accessibility services can observe active app/window context while enabled.
- Microphone audio and transcript/cleanup text may be sent to the providers you configure, such as Groq, Gemini, or OpenAI.
- API keys are tester-provided.
- To stop testing, uninstall the app and remove its saved app data.
- The release APK is signed, but the source snapshot for this exact APK is not yet published in this release lane.

## Honest Boundary

This is a signed sideload preview for people comfortable with Android permissions, Accessibility services, and builder-preview software.

Play Store packaging, public support docs, source publication, and a smoother model-install path are roadmap items.
