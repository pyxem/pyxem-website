Building the docstring works through to steps.

1) Use your local pyxem repo (at the correct commmit hash!) to build the .rst files via

sphinx-apidoc -fo . ../../../pyxem

2) build the html, with 

make html
