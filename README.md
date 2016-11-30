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
* Postgres for storing relational data
* Ack for finding things in files
* The Silver Searcher for finding things fast in vim
* Tmux for saving project state and switching between projects
* Vim 8.0 with lua support
* Exuberant Ctags for indexing files for vim tab completion
* Memcached
* Google Chrome
* Firefox
* iTerm2

It usually takes around 30 minutes to install (depending on your hardware)

macOS Sierra
------------

If you need to pip install psycopg2 run the line below to pull in the command line tools

    xcode-select --install

Credits
-------

This project was heavily inspired by the awesome work at thoughtbot

License
-------

Copyright © 2013 Toran Billups http://toranbillups.com

Licensed under the MIT License
