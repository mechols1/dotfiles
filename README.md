# dotfiles

# Tmux + Fish Cheat Sheet

## 🟢 Starting & Exiting
- `tmux` → start a new tmux session
- `tmux new -s NAME` → start a named session
- `tmux a` or `tmux attach` → reattach to last session
- `tmux a -t NAME` → reattach to a specific session
- `tmux ls` → list all sessions
- `exit` or `Ctrl-d` → close a pane; last pane closes tmux

## 🟢 Prefix Key
- Default prefix = `Ctrl-b`
- Your config sets prefix = `Ctrl-l`
- **All commands below are "prefix + key"**

## 🟢 Window Management
- `c` → create a new window
- `,` → rename window
- `w` → list windows
- `&` → close current window
- `n` / `p` → next/previous window

## 🟢 Pane Management
- `|` → vertical split
- `-` → horizontal split
- `h/j/k/l` → move between panes (vim-style if mapped)
- `N` → break pane into new window
- `x` → close pane

## 🟢 Copy Mode (Vim-style)
- `Ctrl-l [` → enter copy mode
- `v` → begin selection
- `y` → yank selection
- `Escape` → cancel

## 🟢 Reload Config
- `Ctrl-l r` → reload `~/.tmux.conf`

## 🟢 Misc
- `:set-option -g mouse on` → enable mouse temporarily
- `:cclose` / `:lclose` → close quickfix/location list (Neovim, inside tmux)
