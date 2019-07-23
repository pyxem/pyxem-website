# The PyXem Website Repo

[![Build Status](https://travis-ci.org/pyxem/pyxem-website.svg?branch=master)](https://travis-ci.org/pyxem/pyxem-website)

This is the place to edit the website of the pyxem organization. The website can be seen its glory by pointing a browser at https://pyxem.github.io/pyxem-website/

There are two types of pages on the website, "docstring" pages (in the docstring folder here, after the docstring seperator in URLs) are created using the relevant Release version of the main pyxem code by an admin at release time and then uploaded as html to this repo. Most contributors don't need to worry about them.

Files (.rst) in the doc folder meanwhile should be edited in the "normal" way. These are then compiled (by Travis, see .travis.yml) and shortly aftwards the website updates. The final .html files can be found on the gh-pages branch. 

The website is built once a day by Travis so not all merged changes will appear immediately.
