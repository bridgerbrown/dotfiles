# Dotfiles

My dotfiles for symlinking to version controlled files for:
- `.zshrc` shell config
- `.p10k.zsh` shell theme config 
- Ghostty terminal config

## Setup Instructions

### 1. Clone the Repository

```zsh
git clone https://github.com/bridgerbrown/dotfiles.git ~/.dotfiles
```

### 2. Create Symbolic Links

#### .zshrc

```zsh
ln -s ~/.dotfiles/.zshrc ~/.zshrc
```

#### .p10k.zsh

```zsh
ln -s ~/.dotfiles/.p10k.zsh ~/.p10k.zsh
```

#### Ghostty Config

```zsh
ln -s ~/.dotfiles/config.ghostty ~/Library/Application\ Support/com.mitchellh.ghostty/config
```

### 3. Source Files

```zsh
source ~/.zshrc
```

## Making Changes

Edit files directly in `~/.dotfiles/` and changes will be reflected immediately via the symlinks.
