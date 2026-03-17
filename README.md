# GitHub Dark Dimmed for Zed

A GitHub Dark Dimmed theme for the [Zed](https://zed.dev) code editor.

![Theme Preview](./screenshots/preview.png)

> Screenshot: Zed editor with GitHub Dark Dimmed theme showing TypeScript code

## Install

### Manual Installation

1. Copy `themes/github-dark-dimmed.json` to your Zed themes directory:
   - **macOS**: `~/Library/Application Support/Zed/themes/`
   - **Linux**: `~/.config/zed/themes/`

2. Open Zed settings (`Cmd+,` on macOS, `Ctrl+,` on Linux)

3. Add or update the `theme` field:
   ```json
   {
     "theme": "GitHub Dark Dimmed"
   }
   ```

4. Restart Zed if it was open

### Using Zed's Theme Directory

If you already have a themes folder set up:

```bash
# Clone this repo
git clone https://github.com/YOUR_USERNAME/github-dark-dimmed-zed.git

# Copy the theme file
cp github-dark-dimmed-zed/themes/github-dark-dimmed.json \
   ~/Library/Application\ Support/Zed/themes/
```

## Color Palette

### UI Colors

| Color | Hex | Usage |
|-------|-----|-------|
| Background | `#212830` | Main editor background |
| Surface | `#242c36` | Panels, sidebars |
| Editor BG | `#1d242c` | Code editor area |
| Border | `#303945` | Dividers, borders |
| Text | `#adbac7` | Primary text |
| Text Muted | `#768390` | Secondary text |
| Accent | `#4492e9` | Links, focus states |
| Ignored | `#505a6b` | .gitignore files |

### Syntax Highlighting

| Element | Color | Example |
|---------|-------|---------|
| Keywords | `#f47067` | `function`, `return`, `if` |
| Strings | `#96d0ff` | `"hello world"` |
| Functions | `#dcbdfb` | `myFunction()` |
| Types | `#6cb6ff` | `String`, `Array` |
| Numbers | `#6cb6ff` | `42`, `3.14` |
| Comments | `#768390` | `// TODO` |
| Operators | `#adbac7` | `+`, `=`, `=>` |
| Constants | `#6cb6ff` | `PI`, `MAX_VALUE` |

### Terminal Colors

The theme includes a full 16-color ANSI palette matching GitHub's Dark Dimmed terminal theme.

## Why This Theme?

GitHub's Dark Dimmed is easier on the eyes than pure dark themes. The reduced contrast and warm undertones make long coding sessions more comfortable without sacrificing readability.

This port brings that same color scheme to Zed with:
- Careful attention to contrast ratios
- Consistent visual hierarchy
- Full syntax highlighting coverage
- Terminal color support

## Contributing

Found a color that doesn't work well? Open an issue with:
- What you were doing
- What you expected to see
- What you actually saw
- A screenshot if possible

## License

MIT
