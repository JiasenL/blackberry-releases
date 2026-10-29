# Blackberry Live Subtitle

Live subtitles for system audio on Apple Silicon Macs, with local speech recognition and optional translation.

**[Download the latest version](https://github.com/JiasenL/blackberry-releases/releases/latest)**

## Requirements

- Apple Silicon Mac (M1 or later), macOS 15 or later.
- Native Apple Speech requires macOS 26 or later; other recognition models are available on macOS 15+.
- Internet access for the first model and language-pack downloads, and when using Google Translation.

## Install

1. Download the **mac-arm64.dmg** file from the release page.
2. Open it and drag **Blackberry Live Subtitle** into **Applications**.
3. Open the app. It appears in the menu bar.
4. Choose **Start Subtitles** and allow **Screen & System Audio Recording** when prompted.
5. Select a spoken language, recognition model, and optional translation target in Settings. Model downloads and first preparation can take several minutes.

The app is signed with an Apple Development certificate and is **not notarized**. If macOS blocks a trusted download, try opening the app, then use **System Settings → Privacy & Security → Open Anyway**. [Apple's instructions](https://support.apple.com/102445). Managed Macs may restrict this.

A ZIP download and SHA-256 checksums are also provided. From version 0.1.1, use **Check for Updates…** in the menu bar or **Settings → Updates** to download a newer version and choose **Install and Relaunch**. Automatic checks run every six hours and can be disabled in Settings. Update feeds and downloads are verified with cryptographic signatures. Users of version 0.1.0 need to install 0.1.1 manually once to get the updater. Intel Macs and Windows are not supported by these native Mac builds.

## Features

- On-device speech recognition, with models for multilingual speech and Japanese streaming.
- Apple Translation on your Mac, Google Translation (free), or Google Cloud Translation with your API key.
- Translation targets: Simplified Chinese, English, and Korean.
- Configurable rolling subtitles, appearance, keyboard shortcuts, and screen placement.
- Searchable caption history held in memory during the session.
- In-app update checking, downloads, and installation after you choose to restart.

## Privacy

Speech recognition runs locally. Captured audio is not saved. Apple Translation runs locally; selecting a Google translation engine sends caption text to Google. Caption history stays in memory until you start a new session or quit.

This repository hosts downloadable builds. Source is maintained separately. Third-party license notices are included in the app bundle under `Contents/Resources/Licenses`.
