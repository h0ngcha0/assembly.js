assembly.js
===========

Assemble css and js files in the local machine into one HTML file.

For sites like tictail which only allows you to put css and js files in
one gigantic html files, it is mentally impossible to work with it.

This is a simple script that will look at the script and link tag,
check for local css and js files and replace it with whatever
contents that are stored in those files. Everything that is not
accessible by node fs module will be skipped.

This way the js and css files can be organized in a structured way.

usage:
        assembly.js FILE
