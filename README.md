# Configs

Personal config files for the tools I use day to day.

## Tracked Here

- `aerospace/` - Aerospace window manager config.
- `ghostty/` - Ghostty terminal config, icons, and themes.
- `gh/` - GitHub CLI preferences.
- `neofetch/` - Neofetch display config.
- `neovide/` - Neovide GUI config.
- `opencode/` - Opencode config.
- `tmux/` - Tmux config, symlinked from `~/.tmux.conf`.

## Tracked Separately

- `nvim/` - Neovim config, tracked in its own repo:
  `https://github.com/HenryJaiyeoba/nvim-config.git`

## Ignored

- Auth/session state such as GitHub Copilot databases.
- Generated dependencies like `node_modules`.
- App runtime state and logs.
- macOS `.DS_Store` files.

## Useful Commands

```sh
git status
git add aerospace ghostty gh neofetch neovide opencode tmux README.md .gitignore .gitmodules nvim
git commit -m "Update config files"
```
