<div align="center">

<img src="site/social/og.png" width="840" alt="Zyvor Capture: record, trim, edit, share. Screen recording, trim, annotate, cut out, beautify." />

# Zyvor Capture

### Record. Trim. Edit. Share.

Record your screen, trim and tidy the video, and edit screenshots and photos, all in one native macOS 27 menu-bar app that never touches the network.

<br />

**[Download 0.1.0](https://github.com/zyvorai/capture/releases/tag/v0.1.0)** &nbsp;·&nbsp; [Ask for a 30-day trial](mailto:sales@zyvor.dev?subject=Zyvor%20Capture%20trial%20key) &nbsp;·&nbsp; [Website](https://zyvorai.github.io/capture/) &nbsp;·&nbsp; [Docs](docs/INSTALL.md) &nbsp;·&nbsp; [Prices](https://zyvor.dev/pricing)

`ZyvorCapture-0.1.0.dmg` · macOS 27 or later · Apple silicon · Developer ID signed and notarized

</div>

---

## Get it

| | |
| --- | --- |
| **Trial** | A free 30-day trial key: **sales@zyvor.dev**. You do not need a key to use the app. |
| **Download** | [Zyvor Capture 0.1.0](https://github.com/zyvorai/capture/releases/tag/v0.1.0): `ZyvorCapture-0.1.0.dmg` (SHA-256 `9872f1892cb295be21c0b358a7f2dbc3db2ebc3d2459a2f609aeab378099619c`) |
| **Requirements** | macOS 27 or later, Apple silicon |
| **Pricing** | See [zyvor.dev/pricing](https://zyvor.dev/pricing) or write to sales@zyvor.dev. |

## What it does

**Record.** A display, one window or an area, with optional system audio and microphone, a countdown and a hotkey (Control-Option-Command-V). Screenshots with Control-Option-Command-P.

**Trim and export.** Cut a recording to the part you want and export MP4 or an animated GIF.

**Smart edit** (for recordings made in the app, which save pointer positions beside the video):

- **Speed up idle time**, or cut it out, where the pointer neither moves nor clicks. Sped-up parts are silent.
- **Zoom in on clicks**, easing in and out, with optional click rings.
- **Hide sensitive text.** On-device text recognition finds emails, API keys, tokens, private-key headers and card numbers and pixelates them only while they are on screen. It is a helper, not a guarantee: check before you share.

**Photo editor.** Crop and rotate; exposure, contrast, saturation, sharpness and filters; arrows, shapes, text and numbered steps; blur, pixelate or cover to redact; cut out the subject; beautify with a background, rounded corners and a shadow. Export PNG, JPEG or HEIC.

## Privacy and security

- **No network.** Zyvor Capture contains no networking code, and its one special entitlement is the microphone (`com.apple.security.device.audio-input`). Verify: `codesign -d --entitlements - "/Applications/Zyvor Capture.app"`. It is not sandboxed.
- Screen Recording is asked when you first record or take a screenshot; Microphone only if you turn it on.
- It does not log keystrokes. Pointer positions and clicks are saved only beside your recordings, and you can delete that file.

See [docs/PRIVACY.md](docs/PRIVACY.md).

## Limits

- Early release: beyond its automated tests, the real screen capture, the Screen Recording and Microphone prompts, audio, the smart edits on real recordings, VoiceOver and a clean-Mac install have not been tested by us.
- Removing objects from photos is not in this release.

## Trial and licence

30-day trial key: sales@zyvor.dev. Without a key, or after a trial, no data is lost and the app keeps working; a commercial license is required for production use. Licensed under the [Zyvor Production Licence v2.0](LICENSE); see [NOTICE](NOTICE) and [docs/LICENSING.md](docs/LICENSING.md).

**The Zyvor Capture source code is private.** This repository holds documentation and the website.

Copyright © 2026 Zyvor AI Labs Private Limited · [zyvor.dev](https://zyvor.dev)
