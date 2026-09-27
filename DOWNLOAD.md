# Download and install MezaVPN

Use only the files attached to the official [MezaVPN Releases](https://github.com/mehrantabasi/MezaVPN/releases) page.

## Choose the right file

| Device | Release file |
| --- | --- |
| Android 7.0 or newer | `MezaVPN-2.0.0-Android.apk` |
| Most Windows PCs | `MezaVPN-2.0.0-Windows-x64-Setup.exe` |
| 32-bit Windows compatibility | `MezaVPN-2.0.0-Windows-x86-Setup.exe` |
| File verification | `MezaVPN-2.0.0-SHA256SUMS.txt` |

## Android

1. Download the official Android APK from the [latest release](https://github.com/mehrantabasi/MezaVPN/releases/latest).
2. Open the downloaded file and allow installation from your browser or file manager if Android asks.
3. Install MezaVPN. Existing official installations update in place because 2.0.0 uses the same signing identity.
4. Approve Android’s VPN connection permission the first time you connect.

The universal APK supports ARM64, ARMv7, and x86_64 devices and requires Android 7.0 / API 24 or newer. Its package name is `com.mehransystem.mezavpn`.

## Windows

1. Open **Settings → System → About → System type** if you do not know your architecture.
2. Download x64 for a typical modern 64-bit PC. Use x86 only for a 32-bit Windows environment.
3. Verify the installer’s SHA-256 checksum before opening it.
4. Run the installer and accept the Windows UAC prompt. All required runtime components are included; no separate download is required.
5. Leave **Launch MezaVPN** selected on the final page if you want the app to open immediately.

### Unsigned installer notice

The 2.0.0 Windows installers are intentionally distributed without an Authenticode certificate. This does not mean the file has failed its checksum, but Windows SmartScreen may show **Unknown publisher** or **Windows protected your PC** because it cannot establish publisher reputation.

Only after downloading from this repository and confirming the checksum, choose **More info → Run anyway** if SmartScreen blocks the installer. Do not bypass a warning for a file obtained anywhere else.

The installer supports repair and same-architecture upgrades. If MezaVPN is open, setup closes the installed client and stops its service before replacing owned files. Uninstall removes the MezaVPN service, installed files, shortcuts, settings, caches, diagnostics, update files, and MezaVPN-owned AppData/ProgramData content.

## Verify SHA-256

Download `MezaVPN-2.0.0-SHA256SUMS.txt` from the same release, then compare the result for your file.

### Windows PowerShell

```powershell
Get-FileHash .\MezaVPN-2.0.0-Windows-x64-Setup.exe -Algorithm SHA256
```

### Android or desktop tools

Any trusted SHA-256 utility may be used. The hexadecimal result must match the corresponding line in `MezaVPN-2.0.0-SHA256SUMS.txt` exactly.

## Updating

MezaVPN can notify you when an official update is available. Download the new official package and install it over the current version. Windows updates must use the same architecture; uninstall first if you intentionally need to switch between x86 and x64.

## If installation fails

- Download the file again and recheck its SHA-256 value.
- Confirm that the operating system and architecture match the selected package.
- Remove unofficial or differently signed Android copies before installing the official APK.
- Restart Windows if a previous installation is pending a reboot.
- [Open a bug report](https://github.com/mehrantabasi/MezaVPN/issues/new/choose) with the version, OS, architecture, exact message, and sanitized logs.

Never post credentials, private server configurations, or personal data in an issue.
