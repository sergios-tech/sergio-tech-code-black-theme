# Changelog

All notable changes to the "black-sergio-tech" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/).

## [1.0.5] - 2026-04-04

### Fixed

- Removed visible focus border rectangles on 13 UI elements (`focusBorder`, `contrastActiveBorder`, `list.focusOutline`, `list.focusAndSelectionOutline`, `list.inactiveFocusOutline`, `list.filterMatchBorder`, `inputOption.activeBorder`, `commandCenter.activeBorder`, `settings.focusedRowBorder`, `checkbox.selectBorder`, `statusBar.focusBorder`, `statusBarItem.focusBorder`, `inlineChatInput.focusBorder`) by setting them to transparent for a seamless look matching the default theme

### Changed

- Dimmed inactive activity bar icons from `#999999` to `#808080` for a subtler sidebar appearance
- Dimmed status bar foreground from `#cccccc` to `#b3b3b3` for reduced visual prominence

## [1.0.4] - 2026-04-04

### Fixed

- Removed visible `#333333` border rectangles on 38 UI elements (panels, sidebar, editor groups, tabs, terminal, notifications) by setting them to `#000000` for a seamless OLED black look
- Fixed toolbar and Chat button color inconsistency: toned down `commandCenter.activeBorder` to `#a05015`, made `toolbar.hoverOutline` transparent, and unified hover/active backgrounds to `#1a1a1a`

## [1.0.3] - 2026-04-04

### Changed

- **Full brand rebrand**: All UI accent colors migrated from blue (#007fd4 family) to red/orange/gold brand palette matching the Sergio's Tech logo
- Primary accent borders/focus: `#007fd4` → `#e07020` (warm orange)
- Buttons: `#0e639c` → `#b84a10` (deep orange)
- Selection backgrounds: `#04395e` → `#3d1a08` (dark warm red-brown)
- Info/links foreground: `#3794ff` → `#ff8c38` (bright orange)
- Symbol icons: `#75beff` → `#ffb870` (light peachy-orange)
- OLED-dimmed static borders adjusted to `#a05015` (burnt orange)
- Git modified indicators: `#1b81a8` → `#c07018` (warm amber-orange)
- Tab modified borders: `#3399cc` → `#cc7730` (brand orange)

### Fixed

- Terminal ANSI blue readability: `#2472c8` → `#3b8eea` (contrast ~5.5:1 on black)
- Terminal ANSI red readability: `#cd3131` → `#f14c4c` (contrast ~5.2:1 on black)
- `terminalCommandDecoration.successBackground` corrected from blue/orange to green `#2e825c` for semantic consistency
- Removed deprecated `editorIndentGuide.activeBackground` and `editorIndentGuide.background` (numbered variants retained)

### Unchanged (by design)

- Terminal ANSI standard colors, bracket pair colorization, merge conflict incoming (blue), `charts.blue`, all tokenColors syntax highlighting
- Error (#f14c4c), warning (#cca700), and success (#73c991) status colors
- OLED burn-in dimming on static elements (`#e0e0e0` foregrounds, `#a05015` borders)

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
