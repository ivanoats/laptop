Laptop
======

Laptop is a script to set up a Mac OS X laptop for Rails development.

Requirements
------------

1) Install a C compiler. The best thing to do is install [X Code from the Mac App
Store](http://abid.es/XU7YFZ)

*IMPORTANT* DO NOT SKIP THIS STEP

Then:

- Open up the X Code app and choose preferences from the XCode menu.
- Click on the downloads icon
- Make sure the Components section is selected
- Click on install button next to command line tools 

If that doesn't work for some reason:

- Use [OS X GCC Installer](https://github.com/kennethreitz/osx-gcc-installer/) for Snow Leopard (OS X 10.6).

- Use [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action) for Lion (OS X 10.7) or Mountain Lion (OS X 10.8).

2) Open up the Terminal app from /Applications/Utilities. Set zsh as
your login shell by typing this command:

    chsh -s /bin/zsh

Install
-------

Run the script: cut and paste this command into Terminal

    zsh <(curl -s https://raw.github.com/thoughtbot/laptop/master/mac)

What it sets up
---------------

Basically, a pro rails setup.

* Ack for finding things in files
* Bundler gem for managing Ruby libraries
* Foreman gem for serving Rails apps locally
* Heroku Toolbelt for interacting with the Heroku API
* Heroku Config plugin for local `ENV` variables
* Homebrew for managing operating system libraries
* ImageMagick for cropping and resizing images
* Postgres for storing relational data
* Postgres gem for talking to Postgres from Ruby
* Qt for headless JavaScript testing via Capybara Webkit
* Watch for periodically executing a program and displaying the output
* Rails gem for writing web applications
* Redis for storing key-value data
* Ruby stable for writing general-purpose code
* RVM for managing versions of the Ruby programming language
* SSH public key for authenticating with Github and Heroku
* Tmux for saving project state and switching between projects

It should take less than 15 minutes to install (depends on your machine).

Credits
-------

![thoughtbot](http://thoughtbot.com/assets/tm/logo.png)

Laptop is maintained and funded by [thoughtbot, inc](http://thoughtbot.com/community).
The names and logos for thoughtbot are trademarks of thoughtbot, inc.

Thank you, [contributors](/thoughtbot/laptop/graphs/contributors)!

License
-------

Laptop is © 2011-2013 thoughtbot, inc. It is free software, and may be
redistributed under the terms specified in the LICENSE file.
