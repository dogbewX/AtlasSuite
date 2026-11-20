# AtlasSuite
Downloads for the Atlas apps. Each app is signed and notarized by its developer.

## Apps

<!-- apps:start -->
| App | What it does | Version | Download |
| --- | --- | --- | --- |
| AtlasImage <!-- app:atlasimage --> | Screenshot capture and image editor for macOS: capture an area, window or screen, annotate, paint, layers, save in seven formats. | 1.0.0 | [AtlasImage-1.0.0.dmg](https://github.com/dogbewX/AtlasSuite/releases/download/atlasimage-v1.0.0/AtlasImage-1.0.0.dmg) |
| AtlasTerm <!-- app:atlasterm --> | Native macOS multi-agent, multi-terminal manager: run many AI coding agents side by side, see which needs you and jump to it in one keystroke. | 1.0.6 | [AtlasTerm-1.0.6.dmg](https://github.com/dogbewX/AtlasSuite/releases/download/atlasterm-v1.0.6/AtlasTerm-1.0.6.dmg) |
<!-- apps:end -->

<!-- details:atlasimage:start -->
## AtlasImage

A native macOS menu-bar screenshot tool: capture an area, a window or the full screen, send it where you need it, and annotate, paint and save it in seven formats.

Latest: 1.0.0 (2026-11-20) — [Download DMG](https://github.com/dogbewX/AtlasSuite/releases/download/atlasimage-v1.0.0/AtlasImage-1.0.0.dmg) · [zip](https://github.com/dogbewX/AtlasSuite/releases/download/atlasimage-v1.0.0/AtlasImage-1.0.0.zip) · [Release notes](https://github.com/dogbewX/AtlasSuite/releases/tag/atlasimage-v1.0.0)

### What it does

- Capture an area, a window or the full screen (or all displays) with hotkeys you define in Settings › Hotkeys; every hotkey is yours to change.
- A "Choose destination" picker sends each capture to the editor, the clipboard, a file, Mail, the share sheet or a printer, or always uses the destination you pick.
- Editor tools: rectangle, ellipse, line, arrow, text, blur, pixelate, highlight and crop, with undo, a style inspector and a colour palette.
- Paint tools: pencil, brush, marker, airbrush, eraser, fill, colour picker, pixel selections and shapes, plus rotate, flip, skew and invert.
- Layers with show/hide, lock, opacity, rename, reorder, merge and flatten.
- Numbered bullets that count up, in numbers, letters, Roman numerals or a symbol.
- Save As in seven formats: PNG, JPEG, HEIC, TIFF, GIF, BMP and PDF.
- Keep annotations editable: a `.screenshot.json` sidecar next to the image lets you reopen it and edit the annotations later.

### Requirements

- macOS 14 Sonoma or later
- Apple Silicon or Intel Mac

### Install

1. Download the DMG above and open it.
2. Drag **AtlasImage** onto the **Applications** link.
3. Open AtlasImage from Applications and grant Screen Recording permission (System Settings › Privacy & Security › Screen Recording) when you make your first capture.

### Updating

Download the newer DMG from AtlasSuite, quit AtlasImage and drag the new **AtlasImage** into **Applications** to replace the existing copy. There is no auto-update. Your settings and hotkeys are kept.
<!-- details:atlasimage:end -->

<!-- details:atlasterm:start -->
## AtlasTerm

A native macOS multi-agent, multi-terminal manager: run many AI coding agents side by side, see which needs you, and jump to it in one keystroke.

Latest: 1.0.6 (2026-11-20) — [Download DMG](https://github.com/dogbewX/AtlasSuite/releases/download/atlasterm-v1.0.6/AtlasTerm-1.0.6.dmg) · [zip](https://github.com/dogbewX/AtlasSuite/releases/download/atlasterm-v1.0.6/AtlasTerm-1.0.6.zip) · [Release notes](https://github.com/dogbewX/AtlasSuite/releases/tag/atlasterm-v1.0.6)

### What it does

- Run many AI coding agents and plain shells in one window, with live agent state (working, needs input, done) for Claude Code, Codex and Gemini, an attention list and one-keystroke jump.
- Give each session its own git worktree so parallel agents work on separate branches without stepping on each other.
- Organize work with tabs, split panes, grid view and named workspace sections.
- Persist sessions across restarts and resume native agent conversations via optional integrations.
- Keep a command log of every shell command with its exit code and capped output, searchable in the Sessions window and with `atlas commands`.
- Automate and bridge tools with the `atlas` CLI and local socket API.
- Surface background agent status with menu-bar presence and macOS notifications when an agent blocks or finishes.

### Requirements

- macOS 14 Sonoma or later
- Apple Silicon or Intel Mac

### Install

1. Download the DMG above and open it.
2. Drag **AtlasTerm** onto **Applications**.
3. Open **AtlasTerm** from Applications, pick a default folder on first launch, and optionally choose **Settings ▸ Agents** to install the `atlas` command and agent integrations.

### Updating

Download the newer DMG from AtlasSuite, quit **AtlasTerm**, and drag the new **AtlasTerm** into **Applications** to replace the existing copy. There is no auto-update, and your sessions and settings are kept.
<!-- details:atlasterm:end -->
