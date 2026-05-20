# Local Diff Checker

A **100% offline** text comparison tool that runs entirely in your browser. No data is ever sent to any server — your scripts stay on your machine.

## Why?

Online diff checkers like diffchecker.com require you to paste your code into their servers. If you're working with sensitive scripts, proprietary code, or private data, that's a risk. This tool eliminates that concern entirely.

## Features

- **Side-by-side diff view** with line numbers
- **Character-level highlighting** on modified lines
- **Light / Dark theme** toggle
- **Load files** from disk or paste text directly
- **Swap** left and right panels
- **Stats bar** showing additions, deletions, and unchanged lines
- **Zero dependencies** — single HTML file, no install required

## How to Use

Open `DiffChecker.html` in any browser.

## Quick Start

1. Paste or load your **original** text on the left
2. Paste or load your **modified** text on the right
3. Click **Compare ▶**
4. Review the color-coded diff:
   - 🟢 **Green** = added lines
   - 🔴 **Red** = removed lines
   - **Highlighted characters** = inline changes within modified lines
5. Click **← Edit** to go back and make changes

## Files

| File | Description |
|------|-------------|
| `DiffChecker.html` | The main application (single-file, self-contained) |
| `README.md` | This file |

## Privacy

This tool processes everything locally using JavaScript in your browser. **No network requests are made. No data leaves your computer.**

## License

Free to use and modify.
