# Getting started

Getting started is as easy as copy and pasting the boilerplate folder into your working directory. You can remove any files or folders that you will not be using. 

I've included a few helpful starter files to quickly jump into a project and get to work. There is also an included package.json file containing a set of scripts to compile, prefix compress and clean up the files left behind.

If you decide to use the json file included, make sure you fill in your relevant information.


# Main file

The main file (usually labelled main.scss) should be the only Sass file from the whole code base not to begin with an underscore. This file should not contain anything but @import and comments.

Files should be imported according to the folder they live in, one after the other in the following order:

abstracts/
vendors/
base/
layout/
components/
pages/
themes/
In order to preserve readability, the main file should respect these guidelines:

one file per @import;
one @import per line;
no new line between two imports from the same folder;
a new line after the last import from a folder;
file extensions and leading underscores omitted.


# Additional resources

The information within all the readme files is from the sass guidlines:

https://sass-guidelin.es/