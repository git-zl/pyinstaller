==================
PyInstaller Manual
==================

:Version: |PyInstallerVersion|
:Homepage: |Homepage|
:Contact: pyinstaller@googlegroups.com
:Authors: David Cortesi, based on structure by Giovanni Bajo & William Caban, based on Gordon McMillan's manual
:Copyright: This document has been placed in the public domain.


|PyInstaller| bundles a Python application and all its dependencies into
a single package.
The user can run the packaged app without installing a Python interpreter or any modules.
|PyInstaller| supports Python 3.5 or newer,
and correctly bundles the major Python packages
such as numpy, PyQt, Django, wxPython, and others.

|PyInstaller| is tested against Windows, Mac OS X, and GNU/Linux.
However, it is not a cross-compiler:
to make a Windows app you run |PyInstaller| in Windows;
to make a GNU/Linux app you run it in GNU/Linux, etc.
|PyInstaller| has been used successfully with
AIX, Solaris, FreeBSD and OpenBSD
but testing against them is not part of our continuous integration tests.


What's New This Release
~~~~~~~~~~~~~~~~~~~~~~~~

Release 3.0 is a major rewrite that adds Python 3 support,
better code quality through use of automated testing,
and resolutions for many old issues.

Functional changes include
removal of support for Python 2.7,
an easier way to include data files
in the bundle (:ref:`Adding Files to the Bundle`),
and changes to the "hook" API (:ref:`Understanding PyInstaller Hooks`).

Contents:

.. toctree::
   :maxdepth: 2

   requirements
   license
   contributing
   installation
   operating-mode
   usage
   runtime-information
   spec-files
   feature-notes
   when-things-go-wrong
   advanced-topics
   hooks
   bootloader-building
   CHANGES
   CREDITS
   man-pages
   development/index


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. include:: _common_definitions.txt

.. Emacs config:
 Local Variables:
 mode: rst
 ispell-local-dictionary: "american"
 End:
