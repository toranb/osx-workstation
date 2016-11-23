#!/bin/bash

echo "installing homebrew"
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew doctor
brew update

echo "after homebrew is installed update the path"
echo "export PATH='/usr/local/bin:$PATH'\n" >> ~/.bashrc
source ~/.bashrc

echo "fix required before we can install rvm / ruby"
brew install libksba

echo "install rvm / fix gcc / install the latest ruby"
curl -L https://get.rvm.io | bash -s stable --ignore-dotfiles
source ~/.rvm/scripts/rvm
echo "source ~/.rvm/scripts/rvm" >> ~/.bashrc
source ~/.bashrc
sudo ln -s /usr/bin/gcc /usr/bin/gcc-4.2

echo "install the fundamentals"
brew install tig
brew install libjpeg
brew install tree
brew install ack
brew install tmux
brew install htop
brew install the_silver_searcher
brew install postgresql
brew install memcached
brew install zsh-syntax-highlighting
brew install reattach-to-user-namespace --wrap-pbcopy-and-pbpaste

echo "launch memcached on startup"
ln -sfv /usr/local/opt/memcached/*.plist ~/Library/LaunchAgents

echo "add bundler and a few other rails gems"
rvm install 2.3
rvm use 2.3
gem install bundler pg foreman thin --no-rdoc --no-ri

echo "setup pip and virtualenv"
sudo easy_install pip
sudo pip install setuptools --no-use-wheel --upgrade
sudo pip install virtualenvwrapper

echo "add jedi globally for better python support in vim"
sudo pip install jedi

echo "finish the postgres setup"
initdb /usr/local/var/postgres -E utf8

echo "install the latest vim"
brew install python
brew install vim --with-lua

echo "install zsh"
brew install zsh

echo "install exuberant-ctags"
brew install ctags
sudo mv /usr/bin/ctags /usr/bin/ctags_orig

echo "install nvm for better node version management"
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.32.1/install.sh | bash

echo "Setting up homebrew-cask"
brew tap phinze/homebrew-cask
brew install brew-cask

echo "install chrome"
brew cask install google-chrome

echo "install firefox"
brew cask install firefox

echo "install iterm2"
brew cask install iterm2

echo "change the default shell to zsh"
chsh -s /bin/zsh

echo "install virtualbox"
brew cask install virtualbox
