# Crosstalk releases

Installers and update files for **Crosstalk**, a desktop project room where you work with Claude Code and Codex as a team. This repository holds releases only, no source code.

**[Download the latest version](https://github.com/dehydrated1/crosstalk-releases/releases)**

| Platform | File |
| --- | --- |
| Windows 10 or 11 (64-bit) | `Crosstalk-Setup-<version>.exe` |
| macOS, Apple Silicon (M1 and later) | `Crosstalk-<version>-arm64.dmg` |
| macOS, Intel | `Crosstalk-<version>-x64.dmg` |

The `.zip`, `.blockmap` and `.yml` files are used by the app's updater.

## Before you start

Install the agents' own command-line tools and sign in to them: Claude Code (`claude`) and the Codex CLI (`codex login`). Crosstalk runs them with your accounts. Git is needed for Undo, parallel tasks and the Git panel.

## Opening it the first time

- **Windows:** the installer isn't code-signed yet, so SmartScreen may warn. Choose **More info → Run anyway**.
- **macOS:** the app isn't notarized by Apple. Drag it to Applications and open it; when macOS blocks it, go to **System Settings → Privacy & Security** and choose **Open Anyway**. If macOS says the app is damaged, run `xattr -dr com.apple.quarantine /Applications/Crosstalk.app` in Terminal and open it again.

## Updates

Installed copies check this repository for new versions. Windows downloads an update in the background and installs it when you quit. macOS shows a banner that links to the releases page.

## Status

Crosstalk is in beta. Beta versions are published as pre-releases.
