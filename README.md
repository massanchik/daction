daction
=======

Performs custom action in all/specified directories by pattern.

Install:
--------
    pip install daction

Examples:
-------

    daction '/var/www/dir*template' --action='python some_script.py'
    daction '/var/www/dir*template' --action='php composer.phar update'
    daction '/var/www/dir*template' --action='vim some_file.ext'
