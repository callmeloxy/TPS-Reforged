# Changelog

## 1.1.0

### Summary

This update adds automatic performance alerts, Discord webhook support, performance logging, and a default configuration file for TPS Reforged.

### Added

- Added automatic TPS/MSPT performance alerts
- Added configurable alert thresholds for global server performance
- Added configurable alert thresholds for per-dimension performance
- Added Discord webhook support
- Added `/tps webhook test` to test the configured Discord webhook
- Added console logging for performance alerts
- Added file logging for performance alerts
- Added recovery alerts when server performance returns to normal
- Added cooldown support to prevent alert spam
- Added a configurable alert check interval
- Added an option to include dimension performance in alerts
- Added an option to limit the number of dimensions shown in alerts
- Added a default config file in `default_configs/tpsreforged.json`

### Changed

- Changed the main config creation flow to use the default config file included in the mod
- Changed alert behavior to be configurable through `config/tpsreforged.json`

### Notes

- Discord webhook alerts are disabled by default
- To enable Discord alerts, configure the webhook URL in `config/tpsreforged.json`
- TPS Reforged remains a lightweight TPS/MSPT monitoring utility, not a full server profiler

## 1.0.0

### Summary

Initial release of TPS Reforged, a lightweight TPS/MSPT monitor with global and per-dimension performance display.

### Added

- Added `/tps` to display server TPS/MSPT
- Added per-dimension TPS/MSPT display
- Added compact one-line output per dimension
- Added an overall server TPS/MSPT line
- Added `/tps dim <dimension>` to display one specific dimension
- Added `/tps toggle` to enable or disable actionbar TPS display
- Added `/tps status` to check the actionbar status
- Added `/tps reload` to reload the configuration
- Added `/tps help` to display available commands
- Added configurable colors
- Added configurable TPS/MSPT thresholds
- Added configurable dimension display names
- Added automatic config entry generation for unknown dimensions
- Added configurable dimension order
- Added hidden dimension support
- Added configurable line format
- Added configurable actionbar format
- Added French and English translations

### Notes

- The mod is designed to be installed on both client and server
- TPS Reforged is a lightweight monitoring utility, not a full profiler
