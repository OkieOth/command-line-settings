# Purpose
This is a collection of my favourite command line tools.

# Tool
## zsh - The shell
* URL: `https://ohmyz.sh/`
* Install: `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
* to fix color issue in autosuggestions with tmux add this to .zshrc: `export TERM=xterm-256color`

## tmux - Virtual Terminal Manager
* Install: `sudo apt install tmux`

### Commands to use
* URL: `https://github.com/tmux/tmux`
* Some more documentation: `https://wiki.ubuntuusers.de/tmux/`
* create a new session: `tmux new -s SESSION_NAME`
* list existing sessions: `tmux ls`
* attach to an existing session: `tmux attach -t SESSION_NAME`
* detach session: `CTRL-B + d`
* show active session inside tmux: `CTRL-B + S`
* switch to another session pane: `CTRL-B + UP|DOWN|LEFT|RIGHT`
* split window into panes vertical: `CTRL-B + "`
* split window into panes horizontal: `CTRL-B + %`
* turn the split: `CTRL-B + SPACE`
* move a pane to its own window: `CTRL-B + !`
* add a window to another window as pane: `:join-pane -t WND_NR_TO_MOVE_INTO [-h -v]`

## w3m - Web Browser

## trans - Translation tool
* URL: `https://github.com/soimort/translate-shell`
* Install: `sudo apt install translate-shell`
* Simple usage: `trans :en "Ich möchte das nicht"`


## nvim - Editor
* URL: `https://neovim.io/`

