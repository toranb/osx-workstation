OSX Workstation
======

OSX Workstation is a script to set up a Mac OS X for Python/Django development

Requirements
------------

1) Install XCode
2) Install XCode command line tools
3) Pull down this script locally
4) Start the shell script
    sh installer.sh

What it sets up
---------------

* Bundler gem for managing Ruby libraries
* Exuberant Ctags for indexing files for vim tab completion
* Homebrew for managing operating system libraries (OS X only)
* Postgres for storing relational data
* Postgres gem for talking to Postgres from Ruby
* RVM for managing versions of the Ruby programming language
* Ruby stable for writing general-purpose code
* Tmux for saving project state and switching between projects

It usually takes around 60 minutes to install (depends on your hardware)

Credits
-------

This project was heavily inspired by the awesome work at ![thoughtbot](http://thoughtbot.com/assets/tm/logo.png)

License
-------

Copyright © 2013 Toran Billups http://toranbillups.com

Licensed under the MIT License
