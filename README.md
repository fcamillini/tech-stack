# Tech Stack

## Package Manager

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
```

## Development

### Terminal

```bash
brew install --cask kitty
```

### Shell

```bash
brew install zsh
chsh -s /opt/homebrew/bin/zsh

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

brew install lsd
# alias ll='lsd -la'  (add to /zshrc)

brew install tmux
cp tmux.conf ~/.tmux.conf
cp gitconfig ~/.gitconfig
```


### Editors

```bash
brew install --cask visual-studio-code
```

### Development

bash
```
brew install colima # VM Linux che fa girare il demone Docker
brew install docker

brew install uv
```