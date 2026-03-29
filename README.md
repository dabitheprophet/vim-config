# vim-config
my vim config

## Install on a new system

**1. Dependencies**

```bash
sudo apt-get install vim git build-essential cmake python3-dev
```

**2. Clone**

```bash
git clone --recurse-submodules https://github.com/dabitheprophet/vim-config.git ~/vim-config
```

**3. Place config files**

```bash
cp ~/vim-config/.vimrc ~/.vimrc
mkdir -p ~/.vim/bundle
cp -r ~/vim-config/bundle/Vundle.vim ~/.vim/bundle/Vundle.vim
```

**4. Install plugins**

```bash
vim +PluginInstall +qall
```

---

## Keybindings

| Key | Action |
|---|---|
| `Ctrl+n` | Toggle NERDTree file panel |
| `Ctrl+h/j/k/l` | Move between splits |
| `Ctrl+→` | Next buffer |
| `Ctrl+←` | Previous buffer |
| `Ctrl+w` then `s` | Open file in horizontal split (NERDTree) |
| `Ctrl+w` then `v` | Open file in vertical split (NERDTree) |
| `Ctrl+ww` | Cycle between splits |
| `Ctrl+6` | Toggle between last two files |
| `gg=G` | Auto-indent entire file |
| `Ctrl+o` | Jump back to previous cursor position |
| `*` | Search for word under cursor |

