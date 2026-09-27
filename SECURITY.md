# Security Policy

## Supported version

Security fixes are provided for the latest stable version published on the official [Releases](https://github.com/mehrantabasi/MezaVPN/releases) page.

| Version | Supported |
| --- | --- |
| 2.0.x | Yes |
| 1.x | No |

## Download authenticity

Download MezaVPN only from this repository. Every 2.0.0 release includes `MezaVPN-2.0.0-SHA256SUMS.txt`; compare your download before installation.

The official Android package name is `com.mehransystem.mezavpn`. Android 2.0.0 uses the same release-signing identity as previous official MezaVPN APKs and can update them in place.

The Windows 2.0.0 installers are **not Authenticode-signed**. Windows may report an unknown publisher or display SmartScreen. A valid SHA-256 match verifies that the bytes equal the file published here, but it is not a substitute for publisher code signing. Never bypass a Windows warning for a copy obtained outside this repository.

## Reporting a vulnerability

Do not publish credentials, private server details, exploit code, or personal data in a public issue. Use GitHub’s [private vulnerability reporting](https://github.com/mehrantabasi/MezaVPN/security/advisories/new).

A useful report includes:

- Impact and affected platform
- MezaVPN and operating-system versions
- Architecture and device model where relevant
- Reproduction steps
- Sanitized logs or screenshots

Reports made in good faith are appreciated.

**Maintainer:** Mehran Tabasi (Mehran System)
