# LumaForge Hub for Android

Published by **CADET**. Community: https://discord.gg/RK5dyBArdg

[Download the counted Release installer](https://github.com/Crafty56/LumaForge-Android/releases/download/v0.11.0-preview.1/LumaForge-Hub-0.11.0-preview.1.apk)

[Direct file fallback](LumaForge-Hub-0.11.0-preview.1.apk) · [Release history](https://github.com/Crafty56/LumaForge-Android/releases)

Android 8+ and current Android System WebView. Development signed.

The release workflow verifies the committed installer's SHA-256, creates a preview
Release and uploads the same bytes. Existing counted assets are never overwritten.
The workflow runs on relevant pushes or manually from Actions. New installer builds
should use a new version/tag to retain old counters and release history.

To enable the download website, open Settings → Pages → Deploy from a branch →
main → /(root), then save. Its URL is https://crafty56.github.io/LumaForge-Android/ .

The page's primary link uses GitHub Releases, whose public API exposes asset
download_count. A direct-file fallback remains available while publishing is pending.
Counts include repeat requests and do not identify unique people or installs.
Previous raw-file downloads and clicks from a particular referring page cannot
be reconstructed. The optional LumaForge Discord stats app reads both public
platform repositories' Release counters.
