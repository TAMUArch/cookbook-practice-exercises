Exercise 1
==========
Install and configure ntp on and Ubuntu 12.04LTS Server

Tools Needed
------------

* test-kitchen - we use test-kitchen v1 (currently beta)
* foodcritic
* Berkshelf
* Virtualbox
* git

Testing
-------
Set up this cookbook to work with test-kitchen ( https://github.com/opscode/test-kitchen )
using Vagrant, Virtualbox, and Berkshelf.

Requirements
------------

* The NTP service must be installed
* The NTP config must have ntp1..3.tamu.edu as it's primary servers
* The NTP service must be enabled and started
* The NTP Cookbook must have test-kitchen files included and must pass.
* There should be no foodcritic errors.
