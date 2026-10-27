# Dualscan™ Share Suite

Official downloads for macOS, Windows and Chrome.

[Product page and app preview](https://dualscan.cloud/share/) · [Privacy](https://dualscan.cloud/share/privacy.html)

## Downloads · 1.3.0

| Platform | Download |
| --- | --- |
| macOS · Apple silicon | [ARM64 app ZIP](https://github.com/sacs2cd-web/dualscan-os-share-suite/releases/download/v1.3.0/Dualscan-Share-1.3.0-mac-arm64.zip) |
| macOS · Intel | [x64 app ZIP](https://github.com/sacs2cd-web/dualscan-os-share-suite/releases/download/v1.3.0/Dualscan-Share-1.3.0-mac-x64.zip) |
| Windows · 64-bit | [Portable EXE](https://github.com/sacs2cd-web/dualscan-os-share-suite/releases/download/v1.3.0/Dualscan-Share-1.3.0-win-x64.exe) |
| Chrome | [Manifest V3 plugin ZIP](https://github.com/sacs2cd-web/dualscan-os-share-suite/releases/download/v1.3.0/dualscan-share-1.3.0.zip) |

[SHA-256 checksums](https://github.com/sacs2cd-web/dualscan-os-share-suite/releases/download/v1.3.0/SHA256SUMS.txt)

This repository contains download guidance and the distribution license. GitHub's automatically generated ZIP/TAR archives contain that documentation.

<a id="chrome-extension"></a>

## Chrome installation

Use desktop Chrome 132 or newer with File System Access support. Extract the plugin ZIP, open `chrome://extensions`, enable Developer mode, choose **Load unpacked**, and select the extracted folder containing `manifest.json`. Click the Dualscan™ Share toolbar icon. The ZIP contains the files required to run the extension.

## Desktop installation and trust

Extract the Mac ZIP and open the app for your architecture. Run the Windows x64 portable EXE on Windows. Mac apps use ad-hoc signatures without Developer ID or notarization; Windows is unsigned. Windows execution, live AWS/Git-provider publication, physical USB and Samsung restoration acceptance remain untested.

## Original image preservation

SSS derivative saves require every original file and app to match the pinned official reference. Original snapshots remain logically first. Added snapshots use separate validated folders beneath `SmartSwitchBackup2`. Physical folder order and decoded home/tray coordinates are not certified.

Support: [sa.cs2cd@gmail.com](mailto:sa.cs2cd@gmail.com).
