# Changelog v1.0.2

## [Updated to Roblox Version: version-6776addb8fbc4d17]

### Added
- Keybind update system for real-time feature activation
- Watermark fallback to display Place ID
- Custom Models with quick path buttons
- Void Spam, Orbit, Speed, Flight, 360 Spin features

### Fixed
- **Critical**: Misc tab crash fixed
- Removed red UI styling (theme mismatch)
- Custom Models path validation
- Time Changer uses `write_clocktime()`
- ImGui style stack management

### Removed
- **FPS Unlocker** - Prevents future detection by Roblox
- **Desync** - Patched by Roblox
- **Hitsounds** - Reserved for future (not implemented)
- **Red colors** - Theme inconsistency

### Changed
- Simplified Misc tab structure
- Improved keybind handling
- Enhanced error handling

### Known Issues
- **Time Changer** - Buggy, needs rewrite
- **Orbit** - Safe (not detected by anti-cheat)
- Features require proper keybind setup
- Custom Models depends on game state **(Please don't use in games who have good anticheats)**

### Performance
- Void Spam uses random positioning
- Orbit uses 60 FPS limiting
- All features run in separate threads

*Please run the launcher file to receive the update.*
