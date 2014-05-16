OSX Workstation
======

bash script that turns a vanilla macbook pro into a complete python/node/ruby developer machine

Requirements
------------

    1) Install git from the command line (just type git and hit enter)
    2) Pull down this script locally
    3) bash installer


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
* Vim 7.4 and jedi installed globally for improved python auto complete
* Exuberant Ctags for indexing files for vim tab completion
* Virtualbox and Vagrant
* Memcached
* Google Chrome
* Firefox
* Alfred
* iTerm2

It usually takes around 60 minutes to install (depending on your hardware)

Optional -if you find pip install breaks with a strange error code

    1) verify you are running python 2.7.5
    2) if you are, brew install python
    3) verify you now have python 2.7.6 available in /usr/local/Cellar/python
    4) symlink globally to fix the issue apple introduced with Xcode 5.1
    
    sudo ln -sf /usr/local/Cellar/python/2.7.6/bin/python /usr/bin/python

Credits
-------

This project was heavily inspired by the awesome work at thoughtbot

License
-------

Copyright © 2013 Toran Billups http://toranbillups.com

Licensed under the MIT License
