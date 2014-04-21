daction
=======

Performs custom action to all/specified elements in a directory.

Examples:
-------

    daction '/var/www/dir*template' --action='python some_script.py'
    daction '/var/www/dir*template' --action='php composer.phar update'
    daction '/var/www/dir*template' --action='vim some_file.ext'
