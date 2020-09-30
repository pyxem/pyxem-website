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
- 16/09/2020 - diffsims v0.3.0 has been released
- 24/08/2020 - welcoming kikuchipy to the pyxem family 
- 20/08/2020 - orix v0.4.0 has been released
- 08/08/2020 - pyxem v0.12.1 has been released
- 08/01/2020 - Manuscript describing orix is now avaliable on the arXiv (https://arxiv.org/abs/2001.02716)

pyxem packages
--------------

The following packages are developed by the pyxem team:

`pyxem <https://github.com/pyxem/pyxem>`__ - for processing and analysing scanning diffraction data.  

`diffsims <https://github.com/pyxem/diffsims>`__ - for creating diffraction simulations. 

`orix <https://orix.readthedocs.io/en/stable/>`__ - for quaternion, rotation, and orientation handling in Python. 

`kikuchipy <https://kikuchipy.org>`__ - for processing and analysing EBSD data. 

other important packages
------------------------
These packages are central to the scientific functionality of pyxem:

- `HyperSpy <http://hyperspy.org>`__ for multi-dimensional data handling.

- `DiffPy <http://diffpy.org>`__ - for atomic structure manipulation.


.. warning::

    All parts of the pyxem project are under continual development and there may be bugs. As such please use all methods with care.
