# Local Voice

Fully local dictation for macOS. Hold a key, speak Russian, English or both, release: the text
appears at your cursor. Speech recognition runs on your Mac (MLX Whisper); audio and text never
leave it. This repository hosts the downloads and the update feed; the source is private.

## Requirements

- Mac with Apple Silicon (M1 or newer), macOS 14 or newer
- About 2 GB free disk space (app + Fast speech model; the Accurate model adds 3 GB)

## Install

1. Download the latest `LocalVoice-x.y.z.dmg` from [Releases](../../releases/latest).
2. Open the DMG and drag **Local Voice** into **Applications**.
3. Open Local Voice. macOS blocks the first launch because the app is not notarized by Apple:
   open **System Settings > Privacy & Security**, scroll down, click **Open Anyway**, confirm.
   This is needed only once.
4. The Setup window walks you through: Microphone, Accessibility (for the dictation key and
   pasting), and downloading the speech model (1.6 GB, from Hugging Face).

## Use

- Hold **Fn** (or the key chosen in Settings) and speak; release to paste.
- Double-tap the key for continuous Listening Mode.
- If you use Fn: System Settings > Keyboard > "Press 🌐 key to" > **Do Nothing**.

## Updates

Local Voice checks this repository once a day and offers new versions (menu bar icon >
Check for Updates). Updates are signed; the app rejects anything not signed with the
project's key. Your models, history and permissions are kept.
