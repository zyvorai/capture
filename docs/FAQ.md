# FAQ

**What can it record?**

A whole display, one window, or an area you choose, with optional system audio and microphone. Hotkeys: Control-Option-Command-V starts and stops a recording, Control-Option-Command-P takes a screenshot.

**What can I do with a recording?**

Trim it (or trim to where the action is) and export MP4 or an animated GIF at 1080p, 720p or 480p; leave the sound out or export only the sound; grab a frame into the photo editor. Smart edit can speed up or cut idle time, zoom in on clicks, show click rings, spotlight the pointer, frame the video, fade in and out, and pixelate emails, API keys, tokens and card numbers.

**What can I do with a picture?**

Crop (to a shape), rotate, flip, straighten, adjust and filter it; hide secrets with one click; copy its text or read a QR code; add arrows, shapes, text and numbered steps; blur, pixelate or cover parts to redact; cut out the subject; beautify it with a background, rounded corners and a shadow. Export PNG, JPEG or HEIC.

**Why are the zoom and idle tools greyed out for my video?**

They use pointer positions saved beside recordings made in Zyvor Capture (`<name>.cursor.json`). Videos from elsewhere, or without that file, open normally but without those tools.

**Can it really find everything sensitive?**

No. It looks for common patterns in text it can read on screen. It can miss things and can flag harmless text. Check the result before you share.

**Which permissions does it need, and when?**

Screen Recording, the first time you record or take a screenshot; Microphone only if you turn it on.

**Does it send anything over the network?**

No. It contains no networking code. Check with `codesign -d --entitlements - "/Applications/Zyvor Capture.app"`. It is not sandboxed.

**Is there a trial?**

Yes: a 30-day trial key from sales@zyvor.dev. Without a key everything still works.

**What happens without a key, or when a trial ends?**

Nothing is disabled. A status line shows where your licence stands.

**How much does it cost?**

See [zyvor.dev/pricing](https://zyvor.dev/pricing) or write to sales@zyvor.dev.

**Which macOS versions?**

macOS 27 or later, Apple silicon.
