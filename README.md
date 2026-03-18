# GitHub Dark Dimmed for Zed

[![Zed Extension](https://img.shields.io/zed/v/github-dark-dimmed)](https://zed.dev/extensions/github-dark-dimmed)

GitHub's Dark Dimmed theme ported to Zed.

<img src="./screenshots/preview.png" width="400" alt="Theme preview">

## Installation

### From Zed Extension Library

1. Open Zed
2. Press `Cmd+Shift+X` to open extensions
3. Search for "GitHub Dark Dimmed"
4. Click Install

### Manual Installation

Copy the theme file to your Zed themes directory:

```bash
cp themes/github-dark-dimmed.json ~/.config/zed/themes/
```

Then in Zed settings (`Cmd+,` or `Ctrl+,`):

```json
{
  "theme": "GitHub Dark Dimmed"
}
```

## Colors

**Backgrounds**
- Main/UI: `#212830`
- Editor: `#22272e`
- Active line: `#262d35`

**UI**
- Text: `#adbac7`
- Muted: `#768390`
- Borders: `#444c56`
- Accent: `#4492e9`
- Ignored files: `#505a6b`

**Syntax**
- Keywords: `#f47067` (coral red)
- Strings: `#96d0ff` (light blue)
- Functions: `#dcbdfb` (purple)
- Types/Constants: `#6cb6ff` (blue)
- Comments: `#768390` (gray)

Full 16-color terminal palette included.

## Why

The original GitHub Dark Dimmed theme has lower contrast than typical dark themes, making it easier on the eyes during long sessions. This port keeps those same colors.

## Issues

Something looks off? [Open an issue](https://github.com/syxc/github-dark-dimmed-zed/issues) with a screenshot.

## License

MIT
