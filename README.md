This repository covers the following recipe from code.activestate.com:

[COMPUTE MEMORY FOOTPRINT OF AN OBJECT AND ITS CONTENTS](https://code.activestate.com/recipes/577504/)

*Created by Raymond Hettinger on Fri, 17 Dec 2010*

Recursive version sys.getsizeof(). Extendable with custom handlers.

By itself, the builtin function sys.getsizeof() is not helpful determining the size of a container and all of its contents.

This recipe makes it easy to find the memory footprint of a container and its context. Builtin containers and their subclasses are all fully supported. Extensions are provided for user-defined containers.
