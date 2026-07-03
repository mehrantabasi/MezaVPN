<div align="center">

<img src="assets/mezavpn-logo.svg" width="112" height="112" alt="MezaVPN logo">

# MezaVPN

### Private. Fast. Effortless.

A focused Android VPN experience built for quick connections, clear status, and dependable everyday use.

[![Android 7+](https://img.shields.io/badge/Android-7.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/mehrantabasi/MezaVPN)
[![Latest Release](https://img.shields.io/github/v/release/mehrantabasi/MezaVPN?display_name=tag&style=for-the-badge&color=63A8FF)](https://github.com/mehrantabasi/MezaVPN/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/mehrantabasi/MezaVPN/total?style=for-the-badge&color=62E6B5)](https://github.com/mehrantabasi/MezaVPN/releases)

<br>

<a href="https://github.com/mehrantabasi/MezaVPN/releases/latest">
  <img src="https://img.shields.io/badge/Download-Latest%20APK-62E6B5?style=for-the-badge&logo=android&logoColor=07111F" alt="Download latest APK">
</a>

</div>

<br>

<img src="assets/mezavpn-hero.svg" width="100%" alt="MezaVPN — a dependable VPN experience for Android">

## A calmer way to connect

MezaVPN keeps the important things close: a clear connection state, practical server testing, and one-tap control. The interface stays quiet and readable while the connection engine handles the complicated work underneath.

### Highlights

- **Verified connections** — “Connected” appears only after real internet access through the tunnel is confirmed.
- **Smart Failover** — optionally moves to a healthier server when the active connection degrades.
- **Real delay testing** — measures usable end-to-end response instead of relying on a misleading basic ping.
- **Responsive server list** — successful results rise to the top while tests are still running.
- **Lightweight controls** — sensible defaults with advanced tuning available when needed.
- **Broad Android support** — designed for Android 7.0 and newer, including modern phones and x86_64 emulators.
- **No ads or analytics SDKs** — the official build stays focused on the connection experience.

## Download and install

1. Open the [latest release](https://github.com/mehrantabasi/MezaVPN/releases/latest).
2. Download the attached **MezaVPN APK**.
3. Allow installation from your browser or file manager when Android asks.
4. Install the APK and approve the Android VPN permission on first connection.

> Download MezaVPN only from this repository's official **Releases** page. APK files copied to third-party websites may be modified or outdated.

For more detail, see the [installation guide](DOWNLOAD.md).

## Smart Failover

Smart Failover is optional and disabled by default. When enabled, MezaVPN monitors the active tunnel, confirms sustained degradation, checks a short list of strong alternatives, and switches only when the replacement is meaningfully better. Temporary fluctuations do not trigger unnecessary changes.

Available behavior profiles:

- **Stable** — fewer changes and longer confirmation windows.
- **Balanced** — recommended for everyday use.
- **Responsive** — reacts sooner when connection quality changes.

## Requirements

| Requirement | Details |
|---|---|
| Operating system | Android 7.0 (API 24) or newer |
| Architectures | ARMv7, ARM64, x86_64 |
| Permission | Android VPN connection permission |
| Package | `ir.mehransystem.mezavpn` |

## Privacy and security

MezaVPN does not include advertising or analytics SDKs. Connection processing takes place on the device and through the VPN server selected by the app. As with every VPN product, server operators and external services may process technical network information required to deliver their services.

Please read:

- [Privacy Policy](PRIVACY.md)
- [Security Policy](SECURITY.md)

## Support

Found a reproducible problem or have a useful suggestion? Open an issue and include:

- Android version and phone model
- MezaVPN version
- What you expected to happen
- What actually happened
- Relevant logs with credentials and personal information removed

[Open an issue](https://github.com/mehrantabasi/MezaVPN/issues/new/choose) · [View releases](https://github.com/mehrantabasi/MezaVPN/releases) · [Read the changelog](CHANGELOG.md)

## Official distribution repository

This repository contains the official MezaVPN documentation and release downloads. Application source code is not distributed here. MezaVPN is proprietary software; see [LICENSE](LICENSE) for usage terms.

## Developer

**Mehran Tabasi (Mehran System)**  
Designer and developer of MezaVPN

---

<div align="center">

Made with care for a simpler and more dependable Android VPN experience.

</div>
