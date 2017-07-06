# ZSH - OH MY ZSH  
 refer 
 `https://github.com/robbyrussell/oh-my-zsh`
 
 Instruction : 
 ```
 sudo apt-get install zsh
 chsh -s $(which zsh)` unless you are in LDAP or something
 sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
 ```
 
 
 If need to install fonts-powerline :
 `sudo apt-get install fonts-powerline`

# VIM - Vundle :
 `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

# VIM - molokai colorscheme :
 `git clone https://github.com/tomasr/molokai.git`


# Installation

clone repo to ~/.dotfiles folder:
```
cd ~
git clone https://github.com/kwh1210/env-setting.git .dotfiles
```
copy config files by running shell script
```
./install.sh
```
