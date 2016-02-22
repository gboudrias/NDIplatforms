INSTALLATION
============

Download NDIplatforms
---------------------

Download NDIplatforms somewhere convenient, such as:

    :::bash
    $ git clone https://github.com/nditech/NDIplatforms.git ~/makefiles/NDIplatforms
    $ cd ~/makefiles/NDIplatforms


Install Drush
-------------

To use the latest version of NDIplatforms effectively, you need a recent version
of Drush. As such, we recommend using a local Drush install, so as not to
interfere with other Drush functionality on the server.

    :::bash
    $ make drush
     Drush Version   :  8.0.3

Alternatively, you might want to use the latest (unstable) Drush development
build:

    :::bash
    $ make drush-unstable
     Drush Version   :  8.1-dev

You could also deploy Drush from source code:

    :::bash
    $ make drush-source
    Already on 'master'
    [...]
    All settings correct for using Composer
    Downloading...
    [...]
     Drush Version   :  8.1-dev

Finally, deploying Drush from source code allows the use of arbitrary branches
(from a PR, for example):

    :::bash
    $ make drush-source branch=dev/2000
    Switched to branch 'dev/2000'
    [...]
     Drush git branch: dev/2000
