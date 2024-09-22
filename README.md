# Quickstart.nvim

A NeoVim config to get started quickly.

### Installation

Backup your current nvim folders (if any):

```bash
# Linux/Mac
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak

# Windows
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak
Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak
```

Clone the repository:

```bash
# Linux/Mac
git clone https://github.com/moonbrooke/quickstart.nvim.git ~/.config/nvim

# Windows
git clone https://github.com/moonbrooke/quickstart.nvim.git $env:LOCALAPPDATA\nvim
```

(Optional) Remove the .git folder:

```bash
# Linux/Mac
rm -rf ~/.config/nvim/.git

# Windows
Remove-Item $env:LOCALAPPDATA\nvim\.git -Recurse -Force
```

Start Neovim:

```bash
nvim
```
