# Changelog

All notable changes to the "black-sergio-tech" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/).

## [1.0.6] - 2026-04-04

### Changed

- **Full accent rebrand from orange to pure red**: Migrated UI accent color properties from burnt-orange to a pure red palette (#cc0000 family) for a bolder, less eye-straining look

## [1.0.5] - 2026-04-04

### Fixed

- Removed visible focus border rectangles on 13 UI elements by setting them to transparent for a seamless look matching the default theme

### Changed

- Dimmed inactive activity bar icons for a subtler sidebar appearance
- Dimmed status bar foreground for reduced visual prominence

## [1.0.4] - 2026-04-04

### Fixed

- Removed visible border rectangles on UI elements (panels, sidebar, editor groups, tabs, terminal, notifications) for a seamless OLED black look
- Fixed toolbar and Chat button color inconsistency: toned down, and unified hover/active backgrounds to match the new red accent palette while maintaining good contrast on black

## [1.0.3] - 2026-04-04

### Changed

- **Full brand rebrand**: All UI accent colors migrated from blue to red/orange/gold brand palette matching the Sergio's Tech logo

### Fixed

- Terminal ANSI blue readability (contrast on black)
- Terminal ANSI red readability (contrast on black)
- Removed deprecated `editorIndentGuide.activeBackground` and `editorIndentGuide.background` (numbered variants retained)
- OLED burn-in dimming on static elements

## [1.0.2] - 2025-08-08

### Added

- Full coverage for modern VS Code UI tokens: chat/Copilot, command center, inline edit, terminal ANSI colors, testing, and notebooks
- Activated previously commented-out color tokens for complete theme coverage

## [1.0.1] - 2025-04-04

### Changed

- Extension and theme display name from "Sergio's Tech Code Black" to "Sergio's Tech Code in Black (OLED Theme)"

## [1.0.0] - 2026-02-26

### Changed

- `statusBarItem.remoteBackground` color from green (`#159e00`) to black (`#000000`) for a cleaner, consistent look
- `statusBarItem.remoteForeground` color from white (`#ffffff`) to dark red (`#cc0000`) for a more distinctive accent

## [0.1.3] - 2025-02-21

### Changed

- Version bump
- Updated version reference in README

## [0.1.2] - 2025-02-21

### Changed

- Version bump

## [0.1.1] - 2025-02-20

### Added

- Initial release with full dark theme
- Extension icon
- README with website link
