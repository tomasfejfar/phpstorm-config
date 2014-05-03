phpstorm-config
===============

My special tailored PHPStorm config - feel free to add PRs for improvements, but take care to make sure you include ONLY the changes

How to install and use
----------------------

Checkout this repo to `$HOME/.WebIde70` (or .WebIde80 or WebIde60, depending on the version installed - I use current 8 EAP right now). 

But **make sure to backup your config dir first**, just to make sure you won't loose any of your precious setup perks. 

How to commit changes or create PRs
-----------------------------------

PHPStorm creates tons of changes to the folder every time you open it. So best workflow is something like this:

* close PHPStorm
* stash you current changed files
* open PHPStorm, change something in settings
* close PHPStorm
* carefully commit only those files whose changes are relevant
    * there are updates to statistics and some some items in files are in non-deterministic order (generated differently every time)
* reset all the rest
* test the config (optional) 
    * try opening PHPStorm to verify all required settings are present
    * close PHPStorm
    * reset all files again
* pop the stashed code
* fix any conflicts (there should be very few to none)
* continue using PHPStorm with changed configuration
* create pullrequest to add your proposed functionality
