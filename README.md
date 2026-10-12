# Modern Black

A pure black (AMOLED) dark theme for Visual Studio Code.

- True `#000000` backgrounds for the editor, side bar, panels, menus, and title bar
- Thin dark-gray borders and soft white overlays for hover and selection
- Syntax colors from VS Code's **2026 Dark** theme
- Muted red, orange, green, and blue kept for errors, warnings, Git, and diffs

## Install

1. Download `modern-black-1.0.1.vsix` from the Releases page of this repository.
2. In VS Code open Extensions (`Ctrl+Shift+X`), click `...`, and choose **Install from VSIX...**.
3. Pick **Modern Black** with `Ctrl+K Ctrl+T`.

Or from a terminal:

```bash
code --install-extension modern-black-1.0.1.vsix
```

## Build from source

Requires Node.js.

```bash
npx --yes @vscode/vsce package
```

To try the theme without installing, open this folder in VS Code and press `F5`.

## Customize

Everything lives in `themes/modern-black-color-theme.json`:

- `colors` is the interface (same keys as `workbench.colorCustomizations`)
- `tokenColors` is the syntax highlighting

## License

MIT. See `LICENSE`. Syntax colors come from VS Code's 2026 Dark theme; see `THIRD_PARTY_NOTICES.md`.
