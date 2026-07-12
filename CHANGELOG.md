# Changelog

Notable user-facing changes to MezaVPN are documented here.


## 1.2.1

- Added comprehensive country detection from flags, full names, aliases, and ISO codes without changing server titles.
- Added a new subscription source and fast linked-subscription fallback for empty primary feeds.
- Fixed an intermittent reconnect or error state after the user disconnects.
- Kept the first-run Connect button visually active when no servers are loaded.

## 1.2.0

- Added one-tap setup: MezaVPN can update servers, test them, select the fastest responsive option, and connect automatically.
- Improved server-update errors, Ping Test cancellation feedback, and default test performance settings.
- Improved VPN stability when the app moves to the background, with predictable Back and Recent Apps behavior.
- Improved Android launcher-icon sizing across different device masks and launchers.
- Added dynamic app-version metadata and version-aligned server requests.

## 1.1.4

- Fixed false Timeout results during repeated and high-concurrency Ping Tests.
- Aligned native test concurrency with the app setting and improved temporary Xray process cleanup.
- Ensured every server is measured exactly once in each Ping Test.
- Introduced the new MezaVPN brand icon across Android, iOS, the splash screen, and in-app identity.

## 1.1.3

- Added a polished branded splash screen with a smooth transition into the app.
- Made connection failures immediately visible with clear in-card guidance and retry feedback.
- Improved ping results with green responsive states and red Timeout states.
- Added configurable ping concurrency from 1 to 15 and refined default timeout values.
- Improved server selection persistence and reset behavior after server-list updates.
- Restored optional automatic selection of the fastest responsive server after testing.

## 1.1.2

- Added optional Smart Failover with Stable, Balanced, and Responsive behavior.
- Added verified connection state so the interface reports Connected only after real tunnel access succeeds.
- Added ongoing tunnel-health monitoring with protection against transient failures.
- Improved real-delay testing, concurrency control, progress reporting, and cancellation.
- Added automatic ordering of responsive servers by measured delay.
- Improved support for large server lists while keeping the interface responsive.
- Added support for Android 7.0 and newer across ARMv7, ARM64, and x86_64.
- Improved server-list parsing and canonical SHA-256 duplicate detection.
- Improved visual contrast, settings organization, and connection feedback.
