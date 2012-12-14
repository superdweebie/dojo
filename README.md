dojo
====

A package repository to allow dojo install with composer.

To use add the repository, and dependency to your application's composer.json:

    {
        "repositories": [{ "type": "composer", "url": "https://raw.github.com/superdweebie/dojo/master" }],
        "require": {
            "superdweebie/dojo" : "1.8.1"
        }
    }

Other packages
==============

Several other packages are also optionally provided that some dojo users may
find useful.

#dojo/bootstrap

This is a port of twitter bootstrap into the dojo framework. See the
github repo here: http://github.com/xsokev/Dojo-Bootstrap

Install with:

        "require": {
            "dojo/bootstrap" : "dev-master"
        }

#dojo/Sds

This is a range of dojo extensions. See the github repo here:
http://github.com/superdweebie/sijit

Install with:

        "require": {
            "dojo/Sds" : "dev-master"
        }

#twiiter/bootstrap

This is twitter bootstrap itself. See the github repo here:
http://github.com/twitter/bootstrap

Install with:

        "require": {
            "twitter/bootstrap" : "2.1.1"
        }

#fort-awesome/font-awesome

Iconic font designed for twitter bootstrap. See the github repo here:
http://github.com/FortAwesome/Font-Awesome

Install with:

        "require": {
            "fort-awesome/font-awesome" : "2.0.0"
        }
