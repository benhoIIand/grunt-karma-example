grunt-karma-example
===================

An example setup for running Karma through Grunt (using Jasmine)

Install
=======

In order to get started, you'll want to install Install Node.js. When this is installed, you'll need to install Grunt's command line interface (CLI) globally. You may need to use sudo (for OSX, *nix, BSD etc) or run your command shell as Administrator (for Windows) to do this.

`npm install -g grunt-cli`

This will put the grunt command in your system path, allowing it to be run from any directory.

**Note:** that installing grunt-cli does not install the grunt task runner! The job of the grunt CLI is simple: run the version of grunt which has been installed next to a Gruntfile.

Next, run the command:

`npm install`


Use
===

There are currently 2 different Karma tasks setup in the Gruntfile. These are `dev` and `prod`.

** Dev

Running `grunt karma:dev` will run the tests but not kill the test server (the option *singleRun* is set to false). The option *autoWatch* is also set to true, so any file changes made to the source code or tests will re-run the tests.

** Prod

Running `grunt karma:prod` will run the tests once and exit.