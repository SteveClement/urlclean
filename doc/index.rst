.. urlclean documentation master file, created by
   sphinx-quickstart on Tue Jan 24 02:33:21 2012.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to urlclean's documentation!
====================================

urlclean provides functions:

* to follow a http redirect,
* to follow a HTML META redirect,
* to remove Urchin and Facebook tracker URL parameters,
* plugins for futher cleaning power,
* combines all these to unshorten and resolve various URLS

Try it out from the commandline::

  python -m urlclean <some url>

Contents:

.. toctree::
   :maxdepth: 2

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Documentation for the Code
**************************

.. automodule:: urlclean
   :members:

Plugins
*******

Plugins should have a convert function that receives and returns a URL. In case
of an error an unchanged URL should be returned.

Changelog
*********

* v0.5.1 - install/doc fixes
* v0.5 - added plugins

