# Changelog

## ZebraFinder v2

### Added
- BLE-based device discovery
- RSSI display and proximity classes
- Live radar view
- Dynamic radar beep rate based on signal strength
- Nearer / farther trend indicator
- Device naming via Bluetooth name with fallback handling
- GL PIN protection with automatic lock after 5 minutes
- Foreground service for background discoverability
- Remote RING command via GATT
- Android 10 / 11 / 13 / 14 compatibility

### Fixed
- Android 13 BLE scanning compatibility
- Device-name collision that prevented devices with identical names from appearing
- Radar beep audio output
- Live RSSI updates during radar mode

### Notes
- Android 10 requires global Location Services to be enabled for BLE scanning.
- Distance values are approximate and intended only as proximity guidance.
