NDI PLATFORMS
=============

![Build status](https://travis-ci.org/nditech/NDIplatforms.svg)

NDIplatforms is a set of makefiles structured for easy maintenance.  It is used,
along with the [Aegir Hosting System](http://aegirproject.org), to maintain
NDI's [DemTools](https://dem.tools) mass-hosting platform, DemCloud.

Normal usage of NDIplatforms involves simply running Drush Make with one of the
supplied "lock" files.  Lockfiles are simply makefiles with all versions
completely specified.  Further instructions can be found in docs/USAGE.md.

NDIplatforms uses a particular directory layout to make maintaining makefiles
easier.  For a discussion on the reasoning behind this, see docs/STRUCTURE.md.

The maintenance of NDIplatforms leverages a number of features that are new to
Drush 7, along with a custom Drush extension, make_diff.  See docs/INSTALL.md
for a detailed walk-through of installing NDIplatforms and its dependencies.

A specific workflow was developed to maintain the "lock" files.  This workflow
is described in docs/MAINTENANCE.md.

This documentation is managed with [mkdocs](http://www.mkdocs.org/). For
information on getting started, see docs/DOCUMENTATION.md.
