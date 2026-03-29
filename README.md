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

**5. Compile YouCompleteMe**

```bash
cd ~/.vim/bundle/YouCompleteMe
python3 install.py
```

If you don't need code completion, skip step 5 and remove the `YouCompleteMe` line from `.vimrc`.
