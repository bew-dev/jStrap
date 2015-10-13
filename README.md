jStrap

A Grunt JS tasked application base including modern technologies such as bootstrap, jquery, modernizr, less, and more.

Its my first release under this, but its also my first relase to GitHub. I guess you could say im trying to get off on
 the right foot, or is it the left.

This is an application builder that compiles a javascript based application base for new development.  The idea is that
it adds vendor specific functionality;

    - bootstrap
    - modernizr
    - less
    - jade
    - jquery
    - code sniffer
    - jshint
    - uglify
    - cssmin
    - imagemin
    - html-lint
    - htmlclean
    - html-prettyprinter
    
and more.  With this base functionality when you run a couple commands and right away you have your base application
ready to take new code. The standard commands to get started are as follows;

    $ grunt
    
    $ grunt make-bootstrap
    
    $ grunt pull-vendors
    
After you run these commands you will have your base site up and running.  From there, you can test your application to
make sure it works by loading public/ in a browser.  After this, development can begin.

The development process consists of;

    -createview templates using jade
    -create css using less
    -create your js to the js/ dir.
    

Once you are done writing in some code, you can run the following command

    $ grunt
    
This will then run some basic lint/tests on this code, compile it, and shove it into public/ where you can view
it in your browser.

jStrap is in it's early stages so the sky is the limit however the direction i intend to see it head is to morph it into a widely usable, and robust turn-key modern day application starter kit, which will embed the modern necessities automatically so you can stay focused more on development instead of distractions.

Copyright (c) 2013 ICRL
See the file license.txt for copying permission.
This package is licensed under the MIT license.
