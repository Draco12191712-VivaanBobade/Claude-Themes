# Claude Themes

Dark and light themes that make VS Code look like the Claude app.

- **Claude Dark**: Claude's charcoal surfaces (`#151515` editor, `#262626` side bar), warm off-white text and clay orange (`#d97757`) accents.
- **Claude Light**: Claude's near-white surfaces with deeper clay accents.

Both themes cover the whole workbench (side bar, tabs, panels, terminal, menus, quick pick, notifications, diff and merge editors, notebooks, testing, chat and more), not just the editor.

## Code colors

Syntax colors come from Anthropic's brand palette: clay orange strings, tan keywords, pale yellow types, blue functions and soft blue numbers. Semantic highlighting is on, so languages with a language server get the same colors.

The terminal uses the ANSI colors from the Claude app's own code theme.

## Install

1. Open the Extensions view, choose **...** > **Install from VSIX...**, and pick the `.vsix` file.
2. Open **Preferences: Color Theme** (`Cmd+K Cmd+T` / `Ctrl+K Ctrl+T`) and choose **Claude Dark** or **Claude Light**.

To build the `.vsix` yourself, run `npx @vscode/vsce package` in this folder.

## Fonts

VS Code color themes can only change colors, so these themes don't change any fonts. The editor keeps your `editor.fontFamily` setting, and the interface uses your system font.
