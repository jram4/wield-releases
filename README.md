# Wield releases

This repository hosts Wield's public update feed and release downloads. It does not contain Wield's application source or signing private keys.

**[Download Wield Beta 1 — version 1.0 (103)](https://github.com/jram4/wield-releases/releases/download/build-103/Wield-1.0-103.dmg).**

Copy `WieldMac.app` into Applications, launch it, and grant the permissions used by your chosen features. Future releases arrive through Wield's built-in updater. See the [release notes](https://github.com/jram4/wield-releases/releases/tag/build-103).

The universal build targets macOS 13 or later on Apple Silicon and Intel. Installation and the signed 101 → 102 update have been verified on macOS 27 with Apple Silicon. Older macOS versions and physical Intel Macs still need runtime testing.

Releases titled **Wield Update Test** use isolated staging data and are intended for release testing. Use Beta 1 for everyday Wield data.

The update feed is published at <https://jram4.github.io/wield-releases/appcast.xml>. Updates and the feed are signed with Sparkle Ed25519 signatures; application releases also require Developer ID signing and Apple notarization.

Public Sparkle key: `MTJhwUcLOLGfPCyfyIWhkqfhAp4V42t5WovJnFgHf4k=`.
