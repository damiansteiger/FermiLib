FermiLib - An open source software for analyzing quantum simulation algorithms
==============================================================================

.. image:: https://travis-ci.org/ProjectQ-Framework/FermiLib.svg?branch=master
    :target: https://travis-ci.org/ProjectQ-Framework/FermiLib

.. image:: https://coveralls.io/repos/github/ProjectQ-Framework/FermiLib/badge.svg
    :target: https://coveralls.io/github/ProjectQ-Framework/FermiLib

.. image:: https://readthedocs.org/projects/fermilib/badge/?version=latest
	:target: http://fermilib.readthedocs.io/en/latest/?badge=latest
	:alt: Documentation Status


FermiLib is an open source effort for compiling and analyzing quantum simulation algorithms.

The current version is an alpha release which features data structures and tools for obtaining and manipulating representations of fermionic Hamiltonians. FermiLib is designed as a library on top of `ProjectQ <https://github.com/ProjectQ-Framework/ProjectQ>`__ and leverages ProjectQ to compile, emulate and simulate quantum circuits. There are also `plugins <http://projectq.ch/code-and-docs/#Fermilib>`__ available for FermiLib.

Getting started
---------------

To start using FermiLib, follow the installation instructions in the `intro <http://fermilib.readthedocs.io/en/latest/intro.html>`__. There, you will also find `code examples <http://fermilib.readthedocs.io/en/latest/examples.html>`__. Also, make sure to check out the `ProjectQ
website <http://www.projectq.ch>`__ and the detailed `code documentation <http://fermilib.readthedocs.io/en/latest/fermilib.html>`__. Alternatively, consider creating a Docker container defined by the Dockerfile found inside the docker directory. Moreover, take a look at the available plugins for FermiLib.

Plugins
-------

In order to generate molecular hamiltonians in Gaussian basis sets and perform other complicated electronic structure calculations, one can install plugins. We currently support Psi4 (plugin `here <https://github.com/ProjectQ-Framework/FermiLib-Plugin-Psi4>`__, recommended) and PySCF (plugin `here <https://github.com/ProjectQ-Framework/FermiLib-Plugin-PySCF>`__).

How to contribute
-----------------

To contribute code please adhere to the following very simple rules:

1. Make sure your new code comes with extensive tests!
2. Make sure you adhere to our style guide. Until we release a code style 
   guide, just have a look at our code for clues. We mostly follow pep8 and use the pep8 linter to check for it.
3. Put global constants and configuration parameters into src/fermilib/config.py, and
   add *from config import ** in the file that uses the constants/parameters.

Documentation can be found `here <http://fermilib.readthedocs.io/>`_.

Authors
-------

The first release of FermiLib (v0.1a0) was developed by `Ryan Babbush <https://research.google.com/pubs/RyanBabbush.html>`__, `Jarrod McClean <https://crd.lbl.gov/departments/computational-science/ccmc/staff/alvarez-fellows/jarrod-mcclean/>`__, `Damian S. Steiger <http://www.comp.phys.ethz.ch/people/person-detail.html?persid=165677>`__, `Ian D. Kivlichan <http://aspuru.chem.harvard.edu/ian-kivlichan/>`__, `Thomas
Häner <http://www.comp.phys.ethz.ch/people/person-detail.html?persid=179208>`__, `Vojtech Havlicek <https://github.com/VojtaHavlicek>`__, `Matthew Neeley <https://maffoo.net/>`__, and `Wei Sun <https://github.com/Spaceenter>`__.

Questions?
----------

If you have any other questions, please contact fermilib@projectq.ch.

License
-------

FermiLib is released under the Apache 2 license.
