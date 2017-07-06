# ZSH - OH MY ZSH :
 `https://github.com/robbyrussell/oh-my-zsh`
  If need to install fonts-powerline :
    `sudo apt-get install fonts-powerline`

# VIM - Vundle :
 `https://github.com/VundleVim/Vundle.vim`
 
# VIM - molokai colorscheme :
 `https://github.com/tomasr/molokai.git`


# Installation

clone repo to ~/.dotfiles folder:
```
cd ~
git clone https://github.com/kwh1210/env-setting.git .dotfiles
```
create symbolic links to config files
```
ln -s .dotfiles/vimrc .vimrc
ln -s .dotfiles/zshrc-oh-my-zsh .zshrc
ln -s .dotfiles/vim .vim
ln -s .dotfiles/gitconfig .gitconfig
ln -s .dotfiles/gemrc .gemrc
ln -s .dotfiles/emacs .emacs.d
```
