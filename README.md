# Claudy

A dark VSCode theme reverse-engineered from Claude's code preview palette.

---

## Color Palette

| Role            | Color      | Hex       |
| --------------- | ---------- | --------- |
| Background      | Charcoal   | `#30302E` |
| Foreground      | Warm white | `#FAF9F5` |
| Keywords        | Violet     | `#CC7BF4` |
| Functions       | Tangerine  | `#FBAD60` |
| Methods         | Rose       | `#F47B85` |
| Strings         | Lime       | `#9BE963` |
| Numbers / Types | Teal       | `#5EEDED` |
| Comments        | Muted      | `#7A7875` |

---

## Installation

### From the Marketplace

1. Open the **Command Pallete** panel (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Open **Developer: Install Extension From Location...**
3. Locate for **Claudy** and Select Folder
4. Locate **Anthropic Sans** in **/Claudy** and
5. Run **Preferences: Color Theme** and select **Claudy**

## Recommended Font: Anthropic Mono

Claudy was designed alongside **Anthropic Mono**, Claude's monospace typeface. The theme works fine with any monospace font, but Anthropic Mono is the closest match to how Claude's code previews.

> **Note:** VSCode does not allow themes to set fonts. You must install and configure the font yourself.

### How to use Anthropic Mono

1. **Install the font** — double-click `Anthropic Mono.ttf` and click _Install_, or drag it into your system's Fonts folder.
2. Open the **Settings** panel (`Ctrl+,`)
3. Add `'Anthropic Mono Web'` to **Editor: Font Family**. eg. (`'Anthropic Mono Web', Consolas, 'Courier New', monospace`)

## Other Recommended Settings

Optional settings complement the theme well:

```jsonc
{
  // Smooth cursor
  "editor.cursorBlinking": "phase",
  "editor.cursorSmoothCaretAnimation": "on",

  // Bracket pair colours that fit the palette
  "editor.bracketPairColorization.enabled": true,

  // Slightly tighter line height suits the charcoal background
  "editor.lineHeight": 1.6,

  // Indent guides match the theme
  "editor.guides.indentation": true,
  "editor.guides.bracketPairs": "active",
}
```

---

## Language Support

Claudy ships full token + semantic highlighting for:

- JavaScript / TypeScript / JSX / TSX
- Python
- Rust
- Go
- HTML / CSS / SCSS
- JSON / YAML / TOML
- Markdown
- Bash / Shell
- Diff

---

## Changelog

See [CHANGELOG.md](CHANGELOG.md)

---

## License

MIT
