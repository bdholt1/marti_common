^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package swri_nodelet
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.13 (2016-10-23)
-------------------
* Add C++ and CMake macros for wrapper nodes
  Defines a C++ macro to replace the normal nodelet export wrapper that
  also creates a factory function returning a pointer to that nodelet.
  Defines a CMake macro
  swri_nodelet_add_node(NODELET_NODENAME NODELET_NAMESPACE NODELET_CLASS)
  that automatically generates the c++ code for a node wrapper with node
  name NODELET_NODENAME that wraps the nodelet and makes a CMake target
  to build the node.
* Add tests for swri_nodelet with manager and standalone
* Contributors: Ed Venator

0.0.12 (2016-08-14)
-------------------

0.0.11 (2016-05-13)
-------------------

0.0.10 (2016-05-12)
-------------------
* Update version numbers for new packages.
* Version 0.0.10 changelogs.
* Add swri_nodelet package.
  This package simplifies launch files that can easily change between
  running nodelets in a shared manager or as standalone processes.
* Contributors: Edward Venator, Elliot Johnson

* Add swri_nodelet package.
  This package simplifies launch files that can easily change between
  running nodelets in a shared manager or as standalone processes.
* Contributors: Elliot Johnson

0.0.9 (2016-03-04)
------------------

0.0.8 (2016-01-06)
------------------

0.0.7 (2015-11-18)
------------------

0.0.6 (2015-11-17)
------------------

0.0.5 (2015-09-27 15:27)
------------------------

0.0.4 (2015-09-27 11:35)
------------------------

0.0.3 (2015-09-26)
------------------

0.0.2 (2015-09-25 15:00)
------------------------

0.0.1 (2015-09-25 09:06)
------------------------
