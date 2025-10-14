## Requirements

```
brew install fzf bat zoxide ripgrep eza fd starship zsh-completions
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

## Post Install

```
rm -f ~/.zcompdump
chmod -R go-w "$(brew --prefix)/share"
chmod -R go-w "$(brew --prefix)/share/zsh"
```

## Copy this to your ~/.zshrc

```
# All the default terminal-zero aliases and functions
source ~/.local/share/terminal-zero/default/zsh/rc
```
