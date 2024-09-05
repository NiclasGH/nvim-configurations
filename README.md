# Installation
Simply run nvim with this config cloned
Linux
`git clone git@github.com:NiclasGH/NeoVim-Configurations.git ~/.config/nvim`

Windows
`git clone git@github.com:NiclasGH/NeoVim-Configurations.git $env:LOCALAPPDATA\nvim`

## Known dependencies
### Font
Install the [Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.1.1/JetBrainsMono.zip). Should be installed as amin on windows. Linux can use:

```bash
wget -O font.zip https://github.com/ryanoasis/nerd-fonts/releases/download/v3.1.1/JetBrainsMono.zip
unzip font.zip -d fonts
sudo cp -vf fonts/*.ttf /usr/share/fonts
```

### Libs
- gcc
- repgrep
- python3-venv
- tree-sitter-cli

**Linux**
```bash
sudo apt-get install gcc ripgrep unzip python3-venv
cargo install tree-sitter-clim
```

**Windows**
```
choco install neovim llvm ripgrep python3-venv
```
