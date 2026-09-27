# Privacy Policy

**Effective date:** September 27, 2026

MezaVPN is designed to provide Android and Windows VPN connections without advertising SDKs or an account requirement. This policy explains the limited information used by the official MezaVPN applications distributed through this repository.

## Information stored on the device

MezaVPN may store the following information locally so the app can operate correctly:

- Application preferences and connection settings
- Available server profiles
- The selected server
- Recent delay-test results
- The time of the most recent server-list update
- A randomly generated installation identifier used for optional anonymous statistics
- Update and notification preferences
- On Windows, local diagnostics and update files needed for troubleshooting and reliable upgrades

This information remains in the application's private storage unless the user removes the app or clears its data.

## Network activity

To provide its core functionality, MezaVPN makes network requests needed to retrieve service information, test connection quality, establish VPN tunnels, and verify that a tunnel has real internet access.

Connectivity and delay checks may contact widely available endpoints operated by providers such as Cloudflare, Google, or Microsoft. Those providers may receive standard technical information such as the user's IP address, request time, and user agent according to their own privacy policies.

VPN traffic passes through the server selected by the application. Server operators and destination services can process technical information required to provide their services. Users should only connect to servers they trust.

## Optional anonymous usage statistics

MezaVPN may send limited anonymous operational information to the official MezaVPN service to measure installations, active versions, and general product usage. This feature can be disabled at any time in Settings.

The submitted data is limited to:

- A random application installation identifier
- Application version and build number
- Operating-system platform
- On Windows, bounded aggregate counters for app launches, connection attempts,
  successes, failures, cancellations, automatic-mode attempts, unexpected
  disconnects, and total connected time

These Windows counters describe product outcomes only. They do not contain
server names, countries, IP addresses, traffic content, destinations, DNS
activity, configuration values, files, processes, or hardware identifiers.
MezaVPN does not send browsing activity, VPN destinations, selected servers,
configuration contents, contacts, location, advertising identifiers, or
hardware identifiers with these statistics. Standard server access logs may
temporarily contain network information such as an IP address as part of normal
hosting and security operations.

## Notifications

The Android edition uses Firebase Cloud Messaging to deliver optional announcements. Android may request notification permission where required by the operating system. Notification delivery is handled by Google under its applicable terms and privacy practices.

MezaVPN sends notifications through a shared platform topic and does not store individual Firebase device tokens in the MezaVPN management service. If anonymous usage statistics are enabled, opening a notification may submit a random, notification-specific event so aggregate engagement can be measured without building a cross-campaign user profile.

## Information MezaVPN does not intentionally collect

The official application does not include advertising SDKs and does not intentionally collect:

- Browsing history
- The content of communications
- Contact lists, photos, or media
- Precise location
- Advertising identifiers

MezaVPN does not require an account.

## Operational logs

The application and its network infrastructure may produce limited technical logs required for reliability, abuse prevention, or troubleshooting. Hosting and connectivity providers may also retain standard access logs under their own policies. Do not include credentials, private configuration details, or personal information in public GitHub issues.

## Children

MezaVPN is a general-purpose network utility and is not directed specifically to children.

## Changes to this policy

This policy may be updated when the application's behavior or legal requirements change. Material updates will be published in this repository.

## Contact

For privacy questions, open a privacy-related issue in the official repository without including sensitive information:

https://github.com/mehrantabasi/MezaVPN/issues

**Developer:** Mehran Tabasi (Mehran System)
