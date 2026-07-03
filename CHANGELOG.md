# Changelog

Notable user-facing changes to MezaVPN are documented here.

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
