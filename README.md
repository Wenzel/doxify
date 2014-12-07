doxify
======

Quick C++ source code documentation generator based on doxygen
to facilitate understanding of unknown project code structure
and navigate easily into it, thanks to call graphs generation.

usage
------

    ./doxify my_project/src

With `my_project/src` being the root directory of your source code tree.

By default, doxify will generate the documentation in the current directory.
Alternatively, you can specify an output dir :

    ./doxify my_project/src my_project/doc
