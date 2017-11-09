GNAT Collection Library
=======================

Dear GNATCOLL user,

The GNATCOLL project has recently been reorganized with the chief goal of
increasing modularity of individual components. The new design allows for
separate building, installation and deinstallation of components, and
makes it more straightforward to add new ones both in the scope of GNATCOLL
itself and as community contributions.

The current GNATCOLL project has been discontinued. It is replaced by three
separate GitHub projects:

[gnatcoll-core](https://github.com/AdaCore/gnatcoll-core)
- this is the root module

[gnatcoll-bindings](https://github.com/AdaCore/gnatcoll-bindings)
- this is the module that contains bindings to various 3rd party libraries,
  specifically:
   * gmp
   * iconv
   * python
   * readline
   * syslog

[gnatcoll-db](https://github.com/AdaCore/gnatcoll-db)
- this is the module that contains components related to databases,
  specifically:
   * sqlite
   * postgres
   * xref
   * gnatcoll_db2ada
   * gnatinspect

gnatcoll-core is a required component, all others are optional and can be
added to the build on an as-needed basis.

We thank you for your interest in GNATCOLL and hope that you will find
the new organization more convenient to use and contribute to.
