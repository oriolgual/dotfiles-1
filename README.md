# My dotfiles

```bash
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" # Installs homebrew
  brew install git
  git clone git://github.com/oriolgual/dotfiles ~/.dotfiles
  rm ~/.bashrc
  rm ~/.bash_profile
  ln -s ~/.dotfiles/bash_profile ~/.bash_profile
  ln -s ~/.dotfiles/bashrc ~/.bashrc
  ln -s ~/.dotfiles/gitconfig ~/.gitconfig
  ln -s ~/.dotfiles/gitignore ~/.gitignore
  ln -s ~/.dotfiles/vimrc ~/.vimrc
  ln -s ~/.dotfiles/Brewfile ~/Brewfile
  ln -s ~/.dotfiles/tool-versions ~/.tool-versions

  brew bundle
  asdf install
  git clone https://github.com/chriskempson/base16-shell.git ~/.config/base16-shell
  curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
  vim +PlugInstall +qa!
  
```

# Other stuff I need to do

* Set caps lock as ESC
* Set fn as Emoji
* Install certificates
* Setup 1Password
* Set DuckDuckGo as search engine
* Safari settings: show full address, show develop menu, show status bar (command + /)
* Login aws
* gh auth login
