# benchtest - Benchmarking and Testing for C++ [![Build Status](https://travis-ci.org/AE9RB/benchtest.png?branch=master)](https://travis-ci.org/AE9RB/benchtest)

The benchtest library is a benchmark and testing framework for C++.
It requires a C++11 or newer compiler.

This README is for anyone wanting to develop the benchtest library itself.
If you just want to use the benchtest library, begin with the [main documentation]
(http://AE9RB.github.io/benchtest).

## Development Environment

You'll need a few tools to build the tests and documentation. These are
common tools available for all operating systems so you shouldn't have
too much trouble getting them installed.

 * [CMake](http://www.cmake.org)
 * [Doxygen](http://www.doxygen.org)
 * [Graphviz](http://www.graphviz.org)

CMake can create a typical Makefile as well as project files for Xcode,
Visual Studio, and many others. Here's a quick start for Makefile users:

```
$ cmake .
$ make && ctest
$ make doc
```
