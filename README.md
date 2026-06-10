# Tiny Timer

A minimal floating timer widget for Obsidian. Keyboard-first input, theme-aware clock face, procedural alarm — no bloat.

## Features

- **Compact floating widget** that stays out of the way, anchored bottom-right
- **Keyboard-first**: type minutes, press Enter to start
- **Decimal input**: `.5` = 30 seconds, `1.5` = 90 seconds
- **Theme-aware**: uses your Obsidian theme colors
- **Procedural alarm**: short ascending melody, no audio files bundled
- **Multiple timers**: spawn as many as you need
- **Draggable**: reposition anywhere in the workspace
- **Status bar icon**: click the clock icon to spawn a timer

## Commands

| Command | Description |
|---------|-------------|
| **New timer** | Spawn a new timer widget |

## Usage

1. Click the clock icon in the status bar, or use the command palette (`Ctrl/Cmd + P` → "Tiny Timer: New timer")
2. Type a duration in minutes (e.g. `5`, `0.5`, `25`)
3. Press **Enter** or click the play button to start
4. Click play again to pause, or edit the input and press Enter/play to restart with a new duration
5. Close a timer with the **×** button, minimize with **−**

The input field always selects all text on focus for quick editing. Default is 5 minutes; after that, each new timer remembers your last input.

## Clock Face

- Under 12 minutes: displays 12 tick marks (like a clock face)
- 12 minutes and above: displays 60 tick marks (like a watch dial)

## Installation

### From Community Plugins

1. Open **Settings > Community plugins**
2. Search for "Tiny Timer"
3. Click **Install**, then **Enable**

### Manual

1. Download `main.js`, `manifest.json`, and `styles.css` from the [latest release](https://github.com/rezgi/obsidian-tiny-timer/releases/latest)
2. Create a folder `tiny-timer` in your vault's `.obsidian/plugins/` directory
3. Copy all three files into that folder
4. Enable the plugin in **Settings > Community plugins**

## License

MIT
