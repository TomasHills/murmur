# Murmur

Voice dictation for your Mac. Hold a key, speak, let go, and your words appear wherever your cursor is, in any app.

**[Download Murmur for Mac](https://github.com/TomasHills/murmur/releases/latest/download/Murmur.dmg)**

That link always gets the newest version. Past versions and release notes are under [Releases](https://github.com/TomasHills/murmur/releases).

## What it does

- **Private by design.** Speech recognition runs on your Mac (Whisper large-v3 turbo, on the Neural Engine). Your audio never leaves it.
- **Tidies as you speak.** Removes the "um"s and stutters, adds punctuation, and lays your words out: a new paragraph for each point, and a list when you run through items or steps. Say "slash" or "dash" between words to get / or -, and "new paragraph" or "new line" to break exactly where you want. It keeps your words and your tone, swearing included, never adds em dashes, and types a dictated question rather than answering it.
- **Three modes.** Faithful, the default, keeps your words and just punctuates and lays them out. Clean also applies your self-corrections and drops anything you retract. Verbatim types exactly what was heard.
- **Your dictionary.** Add names and terms Murmur should always spell your way.
- **Optional Claude upgrade.** For the sharpest cleanup, add your own Anthropic API key in Settings. Only the text is sent, never audio. Without a key, cleanup stays on your Mac, using Apple Intelligence when it's turned on.

## Requirements

- A Mac with Apple silicon (M1 or later)
- macOS 26 Tahoe or later
- An internet connection on first launch, for a one-time 1.6 GB speech model download

## Install

1. [Download Murmur.dmg](https://github.com/TomasHills/murmur/releases/latest/download/Murmur.dmg) and open it.
2. Drag Murmur into the Applications folder. Always open it from Applications, not from the disk image.
3. The first time, macOS blocks it because it isn't from the App Store or a registered Apple developer. Click **Done**, then open **System Settings > Privacy & Security**, scroll down, click **Open Anyway** and confirm with your password.
4. The setup window walks you through microphone access, accessibility access (so Murmur can type into other apps) and the speech model download. After the download, Murmur optimises the model for your Mac. This can take 10 minutes or more, and dictation starts working as soon as it finishes.

## Using it

Hold **fn** (or the key you choose in Settings), speak, and release. A quick tap starts hands-free dictation; tap again to finish. Press **Esc** to cancel.

## Updating

Download from the same link and install it the same way. Your settings and permissions carry over.

---

Murmur is a personal project, shared as is.
