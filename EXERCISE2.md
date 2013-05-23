Exercise 2 
==========
Install and configure a basic web server using nginx.  Have that web server host
a basic index.html file with the message `I love Chef`.

Tools Needed
------------

* test-kitchen - we use test-kitchen v1 (currently beta)
* foodcritic
* Berkshelf
* Virtualbox

Testing
-------
Set up this cookbook to work with test-kitchen ( https://github.com/opscode/test-kitchen )
using Vagrant, Virtualbox, and Berkshelf.

Requirements
------------

* You may not use external cookbooks!.
* The server should use the official Nginx repo. 
* The message on the web page should be configurable as a node attribute. 
* The directory in which the webpage is located should be configurable as a node attribute. 
* This cookbook should support both Ubuntu 12.04 and Centos 6.3. 
* There should be no foodcritic errors.
