# Changelog

Notable user-facing changes to MezaVPN are documented here.

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
