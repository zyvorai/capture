# Changelog

## v0.6.0 - 2026-11-24

- **Overlays:** title cards and lower thirds, intro and outro cards, a progress bar and step timer, logos, emoji stickers, crop and rotate, auto-reframe to vertical or square that follows your pointer, freeze frame, reverse, eased speed changes and picture-in-picture. The editor's player does not show them; use "Preview this frame" or export.
- **Transcript editing:** write a transcript with word timings, click a word to jump there, delete words to cut that part of the video, and review filler words ("um", "uh") and repeats in one list. Caption looks with a word-by-word highlight. Translate captions and get suggested titles, descriptions and chapter names. Translation and the suggestions use the language models built into macOS, on this Mac, and only appear when your Mac supports them.
- **Guides:** make a step-by-step guide from the clicks in a recording, or from pictures in the library, and save it as Markdown, HTML or PDF.
- **Recording:** timelapse mode; live drawing, a pointer spotlight, a magnifier and click rings while you record, with hotkeys (Control-Option-Command plus D, H, M, K, X, G); copy the latest recording as a GIF from the menu bar.
- **Webcam:** blur or replace the background, filters, bubble shapes and borders, auto-framing on your face, show, hide or move the bubble on a timeline lane, camera-only recording, export the webcam on its own, and a green-screen key.
- **Photo editor:** remove small objects, edit text inside a screenshot, social-media sizes and collages, multi-page PDF, a ruler and a colour contrast checker, replace the background behind a cut-out, curved and shadowed text.
- **App:** change the app's hotkeys, a first-run tour, arrow-key moves in the library, more VoiceOver labels, and a notification when a long export finishes.
- **Not yet tested on real hardware:** these features were checked with automated tests and rendered previews, not in long real recording sessions. Tell us what you find: sales@zyvor.dev.

## v0.5.0 - 2026-11-24

- **Audio:** a waveform lane under the filmstrip; cut or speed up quiet stretches automatically; record a voice-over; add background music that lowers itself under speech; per-clip volume, fades and mute ranges; pick a loudness target (-14, -16 or -23 LUFS).
- **Chapters:** add markers and copy or save YouTube-style chapter text, or SRT and VTT files.
- **Export:** one-click presets for YouTube, TikTok and Reels, X, LinkedIn, Slack and Discord (under 10 MB) and a GitHub README GIF; H.264, HEVC and ProRes 422; better GIFs and animated PNG; save a poster frame, a contact sheet or a folder of frames; export many recordings at once from the library, with a history and filename templates. Animated WebP is not offered because macOS cannot write it.
- **Recording:** pause and resume; show key presses in the video (needs Input Monitoring; "shortcuts only" mode never stores ordinary typing); leave chosen apps out or record only one app; optionally hide desktop icons and the Dock while recording; a teleprompter; instant replay of the last few seconds (up to 15, an Apple limit); start at a set time; a recording area that follows a window. Do Not Disturb is not switched on for you, because macOS gives apps no way to do it. This app's own windows are now left out of recordings by default.
- **Photo editor:** scrolling screenshots; straighten a photographed page; blur faces; browser, phone and laptop frames; new backgrounds and saved looks; polygon, dashed and smoothed strokes; levels, hue, vibrance, tilt-shift, denoise and auto-enhance; apply one recipe to many pictures.
- **App:** a Settings window; library search through spoken words and on-screen text (an index kept in your save folder, which you can delete); tags, favourites, folders and bulk move or trash; offer to clean up old recordings (to the Trash, after asking); Shortcuts actions and optional `capture://` links (off until you turn them on); Quick Look and dragging files out; recent recordings in the menu bar; a permission checklist; an offer to recover a recording that was interrupted.
- **Not yet tested on real hardware:** these features were checked with automated tests and rendered previews, not in long real recording sessions. Tell us what you find: sales@zyvor.dev.

## v0.4.0 - 2026-11-24

- **Undo and redo** in the video editor (Command-Z), with your edits saved beside the video and restored when you reopen it. J, K and L play, and a shortcuts sheet lists the keys.
- **Callouts:** arrows, boxes, circles, text, numbered steps, blur and spotlight that appear for a chosen stretch of the video, on a new Annotations lane or drawn over the player.
- **One-click looks:** Tutorial, Social vertical, Bug report and Clean demo, each a single undo step.
- **Share and size:** AirDrop, Messages, Mail and copy, and "Fit in 10, 25, 50 or 100 MB" exports that re-encode when a file is still too big.
- **Recordings library** as the home screen: thumbnails, search and sorting.
- **Recording:** pick an area with fixed-size presets, stop automatically after a set time, a recording HUD with a menu-bar timer, grab text from the screen or scan a QR code, and a correction for a webcam that starts slightly before the screen.
- **Photo editor:** pen, highlighter, magnifier, spotlight, text styles, stickers, pasted pictures, select and move, canvas expand, before and after, eyedropper and palette, and social-size export.
- **Fixed:** trim, sound-only and timeline exports could fail with a vague error when they ran alongside another export; they now take turns.
- **Not yet tested on real hardware:** the new interactive parts were built and checked in automated tests and rendered previews, not in long real recording sessions. Tell us what you find: sales@zyvor.dev.

## v0.3.0 - 2026-11-23

- **Editable timeline:** zoom, caption, cut and slow-motion blocks sit on lanes under the video that you drag and resize. Zoom blocks are generated from your clicks and can be adjusted or added by hand.
- **New editor layout:** the video editor is now a player, a filmstrip with trim handles and a playhead, and tabs (Trim, Smart edit, Look, Captions, Export). The photo editor's controls are in four tabs, with values and a reset button on every slider.
- **Custom cursor:** optionally record without the system cursor and draw a smoothed, enlarged one afterwards, with a click ring, pulse or glow. Only the export shows it, not the live preview.
- **Webcam:** record the camera beside the screen (a draggable preview bubble that is not recorded), then place it as a circle or rounded bubble in any corner. It follows your cuts and speed changes.
- **Join clips** after the video with a crossfade, dip to black, slide, push or wipe.
- **Captions:** type them, import or save SRT, or write them from speech. Speech recognition runs on this Mac; macOS may download a language pack once the first time you pick a language.
- **Sound:** even out the volume, reduce steady background noise, cut low rumble. Done on this Mac.
- **Video look:** vertical, square and portrait shapes over a blurred copy, a logo, a frame, fades, speed and size choices.
- **Fixed:** the editor's lower controls were cut off at the default window size; long captions ran off the sides of the picture; exports could fail when two ran at once.

## v0.2.0 - 2026-11-23

- **Photo editor:** flip, straighten (cropped so there are no empty corners), crop to a shape (1:1, 16:9, 3:2, 4:3, 9:16, 4:5); warmth, shadows, highlights and vignette; sepia, instant and tonal filters; a macOS window frame with an optional title for sharing; **Find and hide secrets** (emails, keys, card numbers), **Copy text** and **Read QR code**, all on this Mac.
- **Video editor:** spotlight the pointer, frame the video with a background, rounded corners and shadow, fade in and out, 1.5x/2x/4x speed, export at 1080p, 720p or 480p, leave the sound out, export the sound only (M4A), trim to the action, and grab a frame into the photo editor.
- **Screenshots:** optional 3, 5 or 10 second delay, and copy to the clipboard.
- **Changed:** hiding with Pixelate uses larger blocks so a line of text cannot be read.

## v0.1.0 - 2026-11-23

First public release (trial). Requires macOS 27 or later, Apple silicon.

- **Record** a display, a window or an area of the screen, with optional system audio and microphone, a countdown and a hotkey (Control-Option-Command-V). Screenshots with Control-Option-Command-P.
- **Trim** a recording and export it as MP4, or as an animated GIF.
- **Smart edit:** speed up (or cut) the stretches where nothing happens, zoom in on clicks, show click rings, and pixelate emails, API keys, tokens and card numbers automatically. Uses pointer positions saved beside recordings made in the app. Everything runs on this Mac.
- **Photo editor:** crop and rotate, exposure, contrast, saturation, sharpness and filters; arrows, shapes, text and numbered steps; blur, pixelate or cover to redact; cut out the subject; beautify with a background, rounded corners and shadow. Export PNG, JPEG or HEIC.
- Permissions are asked only when first needed (Screen Recording, Microphone). Soft licence: never disables a feature. Free 30-day trial key: sales@zyvor.dev.
