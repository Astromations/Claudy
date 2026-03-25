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

1. Open the **Extensions** panel (`Ctrl+Shift+X` / `Cmd+Shift+X`)
2. Search for **Claudy**
3. Click **Install**
4. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
5. Run **Preferences: Color Theme** and select **Claudy**

### Manual Install (VSIX)

1. Download the `.vsix` file
2. Open the Command Palette and run **Extensions: Install from VSIX...**
3. Select the downloaded file
4. Reload VSCode and select **Claudy** from the colour theme picker

---

## Recommended Font: Anthropic Mono

Claudy was designed alongside **Anthropic Mono**, Claude's monospace typeface. The theme works fine with any monospace font, but Anthropic Mono is the closest match to how Claude's code previews.

> **Note:** VSCode does not allow themes to set fonts — this is a VSCode platform limitation. You must install and configure the font yourself.

### How to use Anthropic Mono

1. **Install the font** — double-click `Anthropic Mono.ttf` and click _Install_, or drag it into your system's Fonts folder.
2. **Set it in VSCode settings** — add this to your `settings.json`:

```jsonc
{
  "editor.fontFamily": "'Anthropic Mono', 'Cascadia Code', Menlo, monospace",
  "editor.fontSize": 13,
  "editor.fontLigatures": false,
}
```

To open `settings.json`: Command Palette → **Preferences: Open User Settings (JSON)**

---

## Other Recommended Settings

These settings complement the theme well:

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

Semantic highlighting is enabled by default. If your language server supports it, you'll get the richest possible colouring automatically.

---

## Changelog

See [CHANGELOG.md](CHANGELOG.md)

---

## License

MIT
