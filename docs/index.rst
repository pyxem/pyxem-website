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

pyxem - Crystallographic Electron Microscopy in Python
======================================================


pyxem is an organisation that develops open-source Python libraries for electron microscopy.
The packages were originally developed as a platform for hybrid diffraction-imaging
microscopy based on scanning electron diffraction (SED) data, but they now do a wide range of things! However, the largest package remains the eponyomous one: pyxem - which is focussed on scanning diffraction.

.. figure:: images/sped_scheme.png
   :align: center
   :width: 600

News
----
- 24/08/2020 - welcoming kikuchipy to the pyxem family 
- 20/08/2020 - orix v0.4.0 has been released
- 08/08/2020 - pyxem v0.12.1 has been released
- 08/01/2020 - Manuscript describing orix is now avaliable on the arXiv (https://arxiv.org/abs/2001.02716)

pyxem packages
--------------

The following packages are developed by the pyxem team:

pyxem - for processing and analysing scanning diffraction data. `Github <http://pyxem.github.io/pyxem/pyxem>`__


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



diffsims - for creating diffraction simulations. `Github <http://pyxem.github.io/pyxem/diffsims>`__

orix - for quaternion, rotation, and orientation handling in Python. `Github <http://pyxem.github.io/pyxem/orix>`__

kikuchipy - for processing and analysing EBSD data. `Github <http://pyxem.github.io/pyxem/kikuchipy>`__

other important packages
------------------------
These packages are central to the scientific functionality of pyxem:

- `HyperSpy <http://hyperspy.org>`__ for multi-dimensional data handling.

- `DiffPy <http://diffpy.org>`__ - for atomic structure manipulation.


.. warning::

    All parts of the pyxem project are under continual development and there may be bugs. As such please use all methods with care.
