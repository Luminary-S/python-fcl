python-fcl
=========

About
-----
This library is a Python binding of FCL library.

Build
-----
Building **python-fcl requires FCL headers and libraries**.
When building, you can specify their location with the --include-dirs
and --library-dirs command line options:

    $ python setup.py build_ext --include-dirs /path/to/includes --library-dirs /path/to/libraries

If you use ubuntu 12.04 and install ros-fcl at /opt directory, you can use the following command:

    $ python setup.py

Install
-------
You can install python-fcl using the normal distutils install command:

    $ python setup.py install

Dependencies
-------------

* numpy
* cython == 0.25
* fcl >= 0.5

