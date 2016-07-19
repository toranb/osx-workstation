OSX Workstation
======

bash script that turns a vanilla macbook pro into a complete python/node/ruby developer machine

Requirements
------------

    1) Install Xcode from the app store
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
* Ack for finding things in files
* The Silver Searcher for finding things fast in vim
* Tmux for saving project state and switching between projects
* Vim 7.4 and jedi installed globally for improved python auto complete
* Exuberant Ctags for indexing files for vim tab completion
* Virtualbox
* Memcached
* Google Chrome
* Firefox
* iTerm2

It usually takes around 30 minutes to install (depending on your hardware)

Required for OSX 10.11

    1) reboot into recovery mode (hold command + R as you boot)
    2) open the terminal application and type `csrutil disable`
    3) reboot and run the script as shown above
    
Credits
-------

This project was heavily inspired by the awesome work at thoughtbot

License
-------

Copyright © 2013 Toran Billups http://toranbillups.com

Licensed under the MIT License
