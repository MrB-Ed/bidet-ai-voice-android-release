# Bidet AI Voice 0.1.0

Initial signed sideload preview for trusted testers.

## Included

- Floating mic overlay for Android text fields.
- Fast cloud STT lane with BYOK setup.
- Optional cleanup lane with BYOK setup.
- Native Walk-and-Talk foreground recording.
- Screen-off recording support through foreground service and wakelock.
- Live timer, transcript box, Copy, Share, and Save.
- Signed release APK, minified and statically verified.

## Known Boundaries

- Sideload only; not a Play Store release.
- Android Accessibility permission is required for text insertion.
- Fresh installs need user-provided API keys for cloud dictation/cleanup.
- On-device STT requires local model setup; the large speech model is not bundled in the APK.
- Release build has static verification; broader device/runtime testing is next.
