# Change Log

All notable changes to the "postrboard" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [2026.416.1] - 2026-04-16

### Fixed
- Restored CalVer versioning (YYYY.MMDD.ITERATION) — previous commits accidentally reverted to semver, causing marketplace version mismatch
- Updated range highlight to warm amber

## [0.1.6] - 2026-04-10

### Fixed
- Updated chat bubble colors to be more clearly blue: light theme now uses `#bae6fd` (sky-200 from palette), dark theme uses `#1a2540` (deep navy)
- Added `chat.requestBubbleHoverBackground` to both themes for distinct hover state

## [0.1.4] - 2026-04-06

### Fixed
- Added statusBarItem hover, active, and prominent colors to both light and dark themes to replace jarring default grey highlights
- Added debuggingBorder to both themes for a polished debug state

## [0.1.0] - 2026-04-01

### Added
- Full VS Code UI theming (183 color keys) — editor, sidebar, activity bar, status bar, tabs, terminal, inputs, buttons, badges, scrollbars, minimap, peek view, diff editor, merge conflicts, git decorations, debug, testing, notifications, bracket colorization, inlay hints, sticky scroll, ghost text, command palette, banners
- 68 syntax highlighting token rules covering JS/TS, HTML, CSS, JSON, YAML, Markdown, JSX/TSX, decorators, template literals
- Semantic highlighting for TypeScript, Python, Rust, Go, Java, C#, C++
- Bracket pair colorization cycling azure → coral → sage
- WCAG AA accessible contrast on all text colors
