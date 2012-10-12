Laptop
======

Laptop is a script to set up a Mac OS X laptop for Rails development.

Requirements
------------

1) Install a C compiler.

Use [OS X GCC Installer](https://github.com/kennethreitz/osx-gcc-installer/) for
Snow Leopard (OS X 10.6).

Use [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action)
for Lion (OS X 10.7) or Mountain Lion (OS X 10.8).

Install
-------

Run the script:

    bash < <(curl -s https://raw.github.com/groupbuddies/laptop/master/mac)

What it sets up
---------------

* Ack for finding things in files
* Bundler gem for managing Ruby libraries
* Homebrew for managing operating system libraries
* ImageMagick for cropping and resizing images
* Postgres for storing relational data
* Postgres gem for talking to Postgres from Ruby
* Qt for headless JavaScript testing via Capybara Webkit
* Rails gem for writing web applications
* Ruby stable for writing general-purpose code
* RVM for managing versions of the Ruby programming language
* SSH public key for authenticating with Github

It should take less than 15 minutes to install (depends on your machine).

Credits
-------

Thanks to [thoughtbot](http://thoughtbot.com/) from whom this scripts are based.

![groupbuddies](http://www.groupbuddies.com/logo.png)

This guides are maintained by [Group Buddies](http://groupbuddies.com)
The names and logos for Group Buddies are trademarks of GB-Software As A Service, Lda.

License
-------

This guides are © 2012 GB-Software As A Service, Lda. It is free software, and may be
redistributed under the terms specified in the LICENSE file.
