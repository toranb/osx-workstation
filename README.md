OSX Workstation
======

bash script that turns a vanilla macbook pro into a complete python/node/ruby developer machine

Requirements
------------

    1) Install XCode
    2) Install XCode command line tools
    3) Pull down this script locally
    4) bash installer

What it sets up
---------------

* Bundler gem for managing Ruby libraries
* Homebrew for managing operating system libraries (OS X only)
* MySQL for storing relational data
* Postgres for storing relational data
* Postgres gem for talking to Postgres from Ruby
* RVM for managing versions of the Ruby programming language
* Ruby stable for writing general-purpose code
* Python + pip + virtualenv + virtualenvwrapper
* PhantomJS for running javascripts headless
* NodeJS for writing javascript build tools
* Ack for finding things in files
* MongoDB for storing documents
* Tmux for saving project state and switching between projects
* Exuberant Ctags for indexing files for vim tab completion (todo)

It usually takes around 60 minutes to install (depending on your hardware)

Credits
-------

This project was heavily inspired by the awesome work at thoughtbot

License
-------

Copyright © 2013 Toran Billups http://toranbillups.com

Licensed under the MIT License
