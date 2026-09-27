# Changelog

This file summarizes notable user-facing changes in official MezaVPN releases.

## 2.0.0 — 2026-09-27

MezaVPN 2.0 is the first coordinated Android and Windows release.

### Android

- Improved Auto Location selection, validation, and connection recovery.
- Added clearer country, city, public identifier, and offline flag presentation.
- Redesigned server cards with stable alignment and meaningful quality colors.
- Improved server refresh behavior while a tunnel is active.
- Reduced unnecessary switching during downloads, uploads, and media playback.
- Reset stale quality measurements after server-list updates.
- Blocked competing quality tests while the VPN is connecting or connected.
- Improved behavior after Wi-Fi or mobile-network changes.

### Windows Native

- Introduced the first native C++ desktop edition for x64 and x86 Windows environments.
- Added Auto and manual connection modes with verified connection status and bounded failure handling.
- Added Unicode search, availability filters, and response/location sorting for server lists.
- Added system-tray controls, startup preference, diagnostics, live traffic details, and guided updates.
- Added architecture-specific offline installers with desktop and Start Menu shortcuts.
- Added in-place repair/upgrade handling and full removal of MezaVPN-owned services, settings, caches, diagnostics, and shortcuts during uninstall.
- Improved responsiveness by separating background work and lowering the priority of intensive probes.
- Improved recovery after sleep, network changes, failed connection attempts, and unexpected tunnel-engine exits.
- Protected locally cached server profiles with Windows user-bound encryption.
- Updated and validated bundled networking components and Windows security hardening.

### Distribution note

- The Windows 2.0.0 installers are unsigned and may trigger Microsoft Defender SmartScreen. Verify the SHA-256 checksum and download only from the official release page.

## 1.4.0

- Added Auto Location for simple one-tap server selection and connection.
- Improved server selection using responsiveness, streaming quality, and connection reliability.
- Added automatic recovery that can move to a verified alternative when the active connection becomes unusable.
- Added seamless manual server switching while the VPN is connected.
- Improved server updates, duplicate removal, connection feedback, and overall stability.

## 1.3.0

- Added built-in update notices with direct access to the latest official download.
- Added optional system notifications for important MezaVPN announcements.
- Added a bilingual About page and official project links.
- Refined startup behavior and overall compatibility.

## 1.2.1

- Improved country detection without changing subscription-provided server titles.
- Added subscription fallback behavior for empty sources.
- Fixed an intermittent reconnect state after disconnecting.

## 1.2.0

- Added one-tap server update, testing, selection, and connection.
- Improved background stability, error feedback, and icon presentation.

## 1.1.4

- Improved repeated and concurrent quality-test accuracy.
- Introduced the current MezaVPN brand identity.

## 1.1.3

- Added the branded splash experience and clearer connection failures.
- Added configurable quality-test concurrency.

## 1.1.2

- Added optional Smart Failover behavior and verified connection status.
- Improved large server-list handling and Android 7.0+ compatibility.
