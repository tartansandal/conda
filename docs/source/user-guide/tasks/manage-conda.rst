==============
Managing conda
==============

.. contents::
   :local:
   :depth: 1


Verifying that conda is installed
=================================

To verify that conda is installed, in your terminal window or an Anaconda Prompt, run:

.. code::

   conda --version

Conda responds with the version number that you have installed,
such as ``conda 4.7.12``.

If you get an error message, make sure of the following:

* You are logged into the same user account that you used to
  install Anaconda or Miniconda.

* You are in a directory that Anaconda or Miniconda can find.

* You have closed and re-opened the terminal window after
  installing conda.


Determining your conda version
==============================

In addition to the ``conda --version`` command explained above,
you can determine what conda version is installed by running
one of the following commands in your terminal window or an Anaconda Prompt:

.. code-block:: bash

   conda info

OR

.. code-block:: bash

   conda -V


Updating conda to the current version
=====================================

To update conda, in your terminal window or an Anaconda Prompt, run:

.. code::

   conda update conda

Conda compares versions and reports what is available to install.
It also tells you about other packages that will be automatically
updated or changed with the update. If conda reports that a newer
version is available, type ``y`` to update:

.. code::

   Proceed ([y]/n)? y
