doxify
======

Quick C++ source code documentation generator based on doxygen
to facilitate understanding of unknown project code structure
and navigate easily into it, thanks to call graphs generation.

Usage
------

    ./doxify my_project/src

With `my_project/src` being the root directory of your source code tree.

By default, doxify will generate the documentation in the current directory.
Alternatively, you can specify an output dir :

    ./doxify my_project/src my_project/doc

Dependencies
-------------

This script obviously depends on `doxygen`, so please install it before.

Otherwise, `doxygen` can make use of `dot` to generate advanced and nicer call graphs.
If the `dot` executable cannot be found on your system, you will get a
warning from `doxify`.
