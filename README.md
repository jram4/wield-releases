# Wield releases

This repository hosts Wield's public update feed and release downloads. It does not contain Wield's application source or signing private keys.

**[Download Wield Beta 11 — version 1.0 (113)](https://github.com/jram4/wield-releases/releases/download/build-113/Wield-1.0-113.dmg).**

Drag `WieldMac.app` into Applications, launch it there, and follow the guided setup and try your everyday app commands on your desktop. Reopen Learn Wield anytime. Send bugs and suggestions with Feedback. Basic usage analytics is enabled when no choice is stored; existing opt-outs are preserved. Events include whether this copy is a beta or stable build. Manage it in Studio → Privacy. Future releases arrive through Wield's built-in updater. See the [release notes](https://jram4.github.io/wield-releases/notes/Wield-1.0-113.html).

The universal build targets macOS 13 or later on Apple Silicon and Intel. Installation and the signed 101 → 102 update have been verified on macOS 27 with Apple Silicon. Older macOS versions and physical Intel Macs still need runtime testing.

Releases titled **Wield Update Test** use isolated staging data and are intended for release testing. Use Beta 11 for everyday Wield data.

The update feed is published at <https://jram4.github.io/wield-releases/appcast.xml>. Updates and the feed are signed with Sparkle Ed25519 signatures; application releases also require Developer ID signing and Apple notarization.

Public Sparkle key: `MTJhwUcLOLGfPCyfyIWhkqfhAp4V42t5WovJnFgHf4k=`.
