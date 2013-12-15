OSX Workstation
======

bash script that turns a vanilla macbook pro into a complete python/node/ruby developer machine

Setup
------------

`curl https://raw.github.com/toranb/osx-workstation/master/installer | bash`


What it sets up
---------------

* Homebrew for managing operating system libraries
* Python + pip + virtualenv + virtualenvwrapper
* RVM for managing versions of the Ruby programming language
* NodeJS and NVM for writing javascript build tools
* MySQL for storing relational data
* Postgres for storing relational data
* PhantomJS for running javascripts headless
* Ack for finding things in files
* Tmux for saving project state and switching between projects
* Custom dotfiles (ZSH specific)
* Vim 7.4 and jedi installed globally for improved python auto complete
* Exuberant Ctags for indexing files for vim tab completion
* Virtualbox and Vagrant
* Google Chrome
* Firefox
* Alfred
* iTerm2

It usually takes around 60 minutes to install (depending on your hardware)

Credits
-------

This project was heavily inspired by the awesome work at thoughtbot

License
-------

Copyright © 2013 Toran Billups http://toranbillups.com

Licensed under the MIT License
