# Changelog

## [1.2.0] - 2026-08-21

### Added

- Circular keyboard navigation between dashboards with the left and right arrow keys.
- Direct dashboard access with the `1` through `9` keys.
- Toggle shortcuts for Edit mode (`D`) and the Add Widget selector (`F`).
- A searchable command palette (`Ctrl/Cmd + K`) for actions, dashboards, and saved links.
- A keyboard-shortcuts reference opened with `?`.
- `Enter` opens the focused link or dashboard for editing while Edit mode is active.

### Changed

- `Esc` now closes open menus and dialogs, cancels a deletion confirmation, and exits Edit mode.
- Redo is now also available with `Ctrl/Cmd + Y` (in addition to `Ctrl/Cmd + Shift + Z`).

## [1.1.0] - 2026-08-10

### Added

- Undo and redo controls for the 10 most recent structural dashboard changes.
- Keyboard shortcuts for undo and redo outside editable fields.
- Custom confirmation dialog for deleting links, widgets, sections, and dashboards.

### Changed

- Destructive actions are now consistently highlighted in red, including the `Delete Link` and `Delete Widget` entries in the link context menu.
- Deletions can be recovered through the session history after confirmation.

## [1.0.0] - 2026-07-04

### Added

- First stable public version.
- Custom Chromium new tab dashboard.
- Editable link collections.
- Local widgets system.
- Browser session widget.
- Uptime monitor widget.
- Local persistence with Chrome storage.

### Changed

- Improved dashboard structure.
- Improved widget layout.
- Improved responsive behavior.
- Cleaned up the first beta implementation.

### Known issues

- Some widgets may still need responsive refinements.
- Some customization flows are still basic.
- The project is functional but still under active development.
