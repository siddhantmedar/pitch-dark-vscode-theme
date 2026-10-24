# Pitch Dark for Ghostty (and cmux)

The same pure black, cyan-accent palette as the VS Code theme, for [Ghostty](https://ghostty.org). cmux reads Ghostty's config, so it works there too.

## Install

```bash
mkdir -p ~/.config/ghostty/themes
curl -fsSL https://raw.githubusercontent.com/siddhantmedar/pitch-dark-vscode-theme/main/extras/ghostty/pitch-dark -o ~/.config/ghostty/themes/pitch-dark
```

Then add this line to `~/.config/ghostty/config`:

```
theme = pitch-dark
```

Reload with `Cmd+Shift+,` (or restart Ghostty).
