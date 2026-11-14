# Wield releases

This repository hosts Wield's public update feed and release downloads. It does not contain Wield's application source or signing private keys.

**[Download Wield Beta 15 — version 1.0 (119)](https://github.com/jram4/wield-releases/releases/download/build-119/Wield-1.0-119.dmg).**

Drag `WieldMac.app` into Applications and open it there. Beta 14 updates automatically. Beta 13 and earlier users: quit Wield and replace the app with this download to move to the new update-signing identity. Keep your saved data. See the [release notes](https://jram4.github.io/wield-releases/notes/Wield-1.0-119.html).

The universal build targets macOS 13 or later on Apple Silicon and Intel. Installation and the signed 101 → 102 update have been verified on macOS 27 with Apple Silicon. Older macOS versions and physical Intel Macs still need runtime testing.

Releases titled **Wield Update Test** use isolated staging data and are intended for release testing. Use Beta 15 for everyday Wield data.

The update feed is published at <https://jram4.github.io/wield-releases/appcast.xml>. Updates and the feed are signed with Sparkle Ed25519 signatures; application releases also require Developer ID signing and Apple notarization.

Public Sparkle key: `Vys2WWh4pNZo7Q2D0rKDXS2xwsNWxUsSQaPWCu0CTq4=`.
