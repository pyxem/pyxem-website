Installation
------------

pyXem requires python 3 and conda - we suggest using the python 3 version of `Miniconda <https://conda.io/miniconda.html>`__ and creating a new environment for pyxem using the following commands in the anaconda prompt:::

      $ conda create -n pyxem
      $ conda activate pyxem

The recommended way to install pyXem is then from conda-forge using:::

      $ conda install -c conda-forge pyxem

Note that pyxem is also available via pip:::

      $ pip install pyxem


Getting Started
---------------

To get started using pyxem, especially if you are unfamiliar with python, we recommend using jupyter notebooks. Having installed pyxem as above, a jupyter notebook can be opened using the following commands entered into an anaconda prompt or terminal:::

      $ conda activate pyxem
      $ jupyter notebook

`Tutorials and Example Workflows <https://github.com/pyxem/pyxem-demos>`__ have been curated as a series of jupyter notebooks that you can work through and modify to perform many common analyses.


Documentation
-------------

Documentation, in the form of `Docstrings <http://pyxem.github.io/pyxem-website/docstring>`__ are available for all pyxem modules at the following links:

- `pyxem.signals <http://pyxem.github.io/pyxem-website/docstring/pyxem.signals>`__ - for manipulating raw data and analysis results.

- `pyxem.generators <http://pyxem.github.io/pyxem-website/docstring/pyxem.generators>`__ - for establishing simulation and analysis conditions.

- `pyxem.components <http://pyxem.github.io/pyxem-website/docstring/pyxem.components>`__ - for fitting in model based analyses.

- `pyxem.libraries <http://pyxem.github.io/pyxem-website/docstring/pyxem.libraries>`__ - that store simulation results needed for analysis.


Questions
---------

If you have a question about pyxem, an issue using the code, or find a bug - we want to know!

We prefer if you let us know by `raising an issue <https://github.com/pyxem/pyxem/issues>`_
on our Github page so that we can answer in "public" and potentially help someone else who has
the same question. You can also e-mail the development team via: pyxem.team@gmail.com


Contributing and Feature Requests
---------------------------------

Developers are recommended to install pyXem by downloading the `source code <https://github.com/pyxem/pyxem>`__ and using the following commands entered into the anaconda promt (or terminal) when located in the pyxem directory:::

      $ conda install -c conda-forge pyxem --only-deps
      $ pip install -e . 

Feature requests, if pyxem doesn't do something you want it to, can be made by
`raising an issue <https://github.com/pyxem/pyxem/issues>`_ or e-mailing the
development team via pyxem.team@gmail.com

Contributions from new developers are strongly encouraged. Many potential contributors
may be scientists with little or no open-source development experience and we have written
a contributing guide, which you can find on the github.

