# Helix Cheat Sheet

A one-page visual cheat sheet for the [Helix](https://helix-editor.com) modal text editor.

**[Open the cheat sheet →](https://qcpunks.github.io/helix-cheatsheet/)**

## What's inside

- **The core idea:** Helix selects first, then acts (`w` then `d` deletes a word). This is the reverse of Vim.
- Modes, movement, word and line navigation
- Editing actions and common combos (`xd` delete line, `xy` copy line, `U` redo)
- Selection and multiple cursors (`C`, `s`, `,`)
- Command mode, the Space menu, Goto (`g`) and window (`Ctrl+w`) menus
- LSP features: go to definition, references, code actions, symbols
- A "master these first" list for day one

## Use it offline

Download `helix-cheatsheet.html` and open it in any browser. It's a single file with no build step.

## Practice

Helix ships with an interactive tutorial:

```sh
hx --tutor
```

## Contributing

Found a wrong or missing keybinding? Open an issue or a pull request. Keybindings follow Helix's default keymap ([docs](https://docs.helix-editor.com/keymap.html)).

## License

[MIT](LICENSE) © Jevante B. / QCP Studio
