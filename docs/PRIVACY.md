# Privacy

- **No network.** Zyvor Capture contains no networking code. Its special entitlements are the microphone (`com.apple.security.device.audio-input`) and the camera (`com.apple.security.device.camera`). It is **not** sandboxed. Verify:

```
codesign -d --entitlements - "/Applications/Zyvor Capture.app"
```

- **What it records.** Only what you point it at: a display, window or area, plus system audio and the microphone if you turn them on. Files are written to the folder you choose and go nowhere else.
- **Webcam.** Only if you turn it on. It is recorded to a separate file beside the recording and stays on this Mac. The preview bubble is not recorded.
- **Speech to captions.** Uses the on-device recognizer in macOS. Audio is not sent anywhere. The one network use is macOS itself downloading a language pack the first time you choose a language that is not installed; our app has no networking code.
- **Pointer data.** While recording, the app notes where the pointer is and when you click, relative to the recorded area, and saves it as `<recording>.cursor.json` beside the video. It does not log keystrokes or what you type.
- **Sensitive-text hiding.** The scan for emails, keys and card numbers uses on-device text recognition. Nothing is uploaded. It is a helper, not a guarantee: check the result before you share a video.
- **Photo and video edits** happen on this Mac.
- **Licence.** A key is verified on your Mac against a built-in public key. The app cannot create keys and sends nothing.
