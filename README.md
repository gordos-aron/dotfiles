# Dotfiles Setup 🚀

## Steps

1. Clone this repo.

```zsh
# SSH
git clone git@github.com:gordos-aron/dotfiles.git ~/dotfiles

# HTTPS
git clone https://github.com/gordos-aron/dotfiles.git ~/dotfiles
```

2. Create symlinks in the Home directory.

```zsh
# .zshrc
ln -s ~/dotfiles/.zshrc ~/.zshrc

# .gitconfig
ln -s ~/dotfiles/.gitconfig ~/.gitconfig

# Visual Studio Code
ln -s ~/dotfiles/settings.json ~/Library/Application\ Support/Code/User/settings.json
```
