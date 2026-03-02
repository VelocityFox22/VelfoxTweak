# Changelog

All notable changes to Velfox Tweaks are documented in this file.

---

## [v0.5.3] - 2026-03-02

### Improvements

- Enhanced the internal logic to:
  - Automatically skip execution when the target path does not exist.
  - Avoid redundant write operations when the current value already matches the intended value.

  This optimization improves script execution efficiency, reduces unnecessary system calls, and minimizes I/O overhead during daemon operation.

- Added Tx and Rx network tuning to improve throughput stability and latency consistency.
- Disabled Adreno limiter handling to provide more consistent GPU scaling behavior.
- Improved the CPU lock mechanism to ensure safer and more universal behavior across different kernel implementations.
- Refactored the overall script structure for improved maintainability, readability, and execution clarity.
- Corrected typographical issues and removed redundant or duplicated code segments.

- Daemon engine optimized:
  - Improved daemon execution speed and responsiveness.
  - Reduced loop latency and unnecessary polling cycles.
  - Optimized task scheduling logic for better runtime efficiency.
  - Lowered resource footprint while maintaining aggressive performance tuning.
  - Increased overall effectiveness of background monitoring and enforcement.

  These improvements significantly enhance daemon stability, reduce overhead during continuous operation, and ensure faster application of performance profiles.

### Changes

- Renamed operational modes:
  - Apex → Esport
  - Adaptive → Balanced

  The updated naming improves clarity and better reflects the purpose of each performance profile.

### Stability and Compatibility

- Reduced unnecessary kernel write operations.
- Lowered background I/O overhead.
- Improved cross-SoC compatibility and overall daemon reliability.
