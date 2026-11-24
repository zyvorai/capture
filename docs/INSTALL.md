# Install Zyvor Capture

Requires macOS 27 or later on Apple silicon. Zyvor Capture is a menu-bar app; its windows open when you record, take a screenshot or open a file.

## 1. Download and verify

Download [ZyvorCapture-0.4.0.dmg](https://github.com/zyvorai/capture/releases/download/v0.4.0/ZyvorCapture-0.4.0.dmg) and its `.sha256` file from the [release page](https://github.com/zyvorai/capture/releases/tag/v0.4.0). The DMG is Developer ID signed and notarized by Apple.

```
shasum -a 256 -c ZyvorCapture-0.4.0.dmg.sha256
xcrun stapler validate ZyvorCapture-0.4.0.dmg
```

SHA-256 of this release: `f51220b88a1d3230b68ea244daeb243954e660022ec9780f723e8a73532d5037`.

## 2. Install

Open the DMG, drag **Zyvor Capture** to Applications and open it. A Welcome window explains each permission before anything is requested.

## 3. Trial key

You do not need a key. For a 30-day trial key write to sales@zyvor.dev and enter it under **Licence…** in the menu. See [LICENSING.md](LICENSING.md).

## Permissions

- **Screen Recording** is requested the first time you record or take a screenshot. macOS may ask you to restart the app after you allow it.
- **Microphone** is requested only if you turn the microphone on.
- **Camera** is requested only if you turn the webcam on.
- **Speech Recognition** is requested only when you ask for captions from speech. macOS may download a language pack once.
- Pointer positions and clicks (for zoom and idle detection) need no permission and are saved only beside your recordings.

Open **System Settings > Privacy & Security** to change any of them later.

## Where files go

Recordings are saved in your Movies folder unless you choose another folder. A recording made in the app has a small `.cursor.json` file beside it; delete it any time and only the zoom and idle tools turn off.

## Uninstall

Quit Zyvor Capture and delete it from Applications. Your recordings stay where you saved them.
