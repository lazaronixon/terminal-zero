<img width="960" height="540" alt="background" src="https://github.com/user-attachments/assets/35012f6c-5507-4fb5-b893-080585bc0362" />

## Requirements

```
brew install font-meslo-lg-nerd-font fzf bat zoxide ripgrep eza fd zsh-completions starship
```

## Installation

### Clean Up

```
rm -rf ~/.config/starship.toml
rm -rf ~/.local/share/terminal-zero
```

### Install Terminal Zero

```
git clone https://github.com/lazaronixon/terminal-zero ~/.local/share/terminal-zero
cp -r ~/.local/share/terminal-zero/config/* ~/.config/
```

```
rm -f ~/.zcompdump
```

## Add this to the top of your ~/.zshrc file

```
# All the default terminal-zero aliases and functions
source ~/.local/share/terminal-zero/default/zsh/rc
```

## Set font

Set the font in your terminal emulator to "MesloLGL Nerd Font".

## Guides

- [The Omarchy Manual - Shell Tools](https://learn.omacom.io/2/the-omarchy-manual/57/shell-tools)
- [The Omarchy Manual - Prompt](https://learn.omacom.io/2/the-omarchy-manual/95/prompt)
