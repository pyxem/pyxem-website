.. pyxem documentation master file, created by
   sphinx-quickstart on Fri Sep 16 14:34:23 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. toctree::
    :hidden:

    self


.. figure:: images/forkme_right_orange_ff7600.png
    :align: right
    :target: https://github.com/pyxem/pyxem

pyXem - Crystallographic Electron Microscopy in Python
======================================================

.. image:: https://travis-ci.org/pyxem/pyxem.svg?branch=master
    :target: https://travis-ci.org/pyxem/pyxem

.. image:: https://ci.appveyor.com/api/projects/status/github/pyxem/pyxem?svg=true&branch=master
    :target: https://ci.appveyor.com/project/dnjohnstone/pyxem/branch/master

.. image:: https://coveralls.io/repos/github/pyxem/pyxem/badge.svg?branch=master
    :target: https://coveralls.io/github/pyxem/pyxem?branch=master

.. image:: http://img.shields.io/pypi/v/pyxem.svg?style=flat
    :target: https://pypi.python.org/pypi/pyxem

.. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.2649351.svg
   :target: https://doi.org/10.5281/zenodo.2649351

pyXem is an open-source Python library for crystallographic electron microscopy.
The code is primarily developed as a platform for hybrid diffraction-imaging
microscopy based on scanning electron diffraction (SED) data.

.. figure:: images/sped_scheme.png
   :align: center
   :width: 600

pyXem is released under the GPL v3 license.

If analysis using pyxem forms a part of published work please consider recognizing the
code development by citing the DOI at the top of this page.

News
----
- 14/02/2020 - pyxem has a new release (https://github.com/pyxem/pyxem/releases/tag/v0.10.1)
- 08/01/2020 - Manuscript describing orix is now avaliable on the arXiv (https://arxiv.org/abs/2001.02716)

Related Packages
----------------

The following packages are developed by the pyXem team:

- `orix <http://pyxem.github.io/pyxem/orix>`__- for quaternion, rotation, and orientation handling in Python.


These packages are central to the scientific functionality of pyXem:

- `HyperSpy <http://hyperspy.org>`__ for multi-dimensional data handling.

- `DiffPy <http://diffpy.org>`__ - for atomic structure manipulation.


.. warning::

    The pyXem project is under continual development and there may be bugs. All methods must be used with care.
