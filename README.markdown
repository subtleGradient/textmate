textmate
========

Provides package management for TextMate.

Installation
------------
###`sudo gem install wycats-textmate --source=http://gems.github.com`

Usage
=====

###`textmate [COMMAND] [*PARAMS]`

Commands
-------
###`remote [SEARCH] [--source=SOURCE] [--verbose]`
Lists all the matching remote bundles from the matching source.

###`list [SEARCH]`
lists all the matching bundles installed locally.

###`install NAME [--source=SOURCE] [--verbose]`
Install a bundle from the matching source.

###`uninstall NAME`
Uninstall a bundle. Moves the bundle `NAME.tmbundle` to the trash from every local bundle path

###`reload`
Tell TextMate to Reload all Bundles from the filesystem. Textmate bundles are automatically reloaded after `install` or `uninstall` operations.

###`help [TASK]`
describe available tasks or one specific task
