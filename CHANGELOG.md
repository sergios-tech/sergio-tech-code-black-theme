# Changelog

All notable changes to the "black-sergio-tech" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/).

## [1.0.2] - 2025-08-08

### Added

- Full coverage for modern VS Code UI tokens: chat/Copilot, command center, inline edit, terminal ANSI colors, testing, and notebooks
- Activated ~900 previously commented-out color tokens for complete theme coverage

### Fixed

- `header` scope foreground changed from invisible `#000080` to readable `#3794ff`
- Peek view backgrounds changed from `#001a1a` (teal tint) to `#000000` (true OLED black)
- Added missing newline at end of theme file

### Changed

- `editor.selectionBackground` from bright `#007acc` to subtle `#04395e` for a more OLED-appropriate look
- `editorGroup.border` from invisible `#000000` to visible `#333333`
- `activityBarBadge.background` from `#000000` to `#007acc` for visible notification badges

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
