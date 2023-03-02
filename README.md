# Hard Trees Data

This repository contains the results of the paper *The Smallest Hard Trees*. The
companion code can be found
[here](https://github.com/WhatDothLife/TheSmallestHardTrees).

# Project Data Directory Structure
-----------------

This repository contains data for trees with up to 22 vertices, categorized by
type and number of vertices. The orientation data is stored as text files
containing edge lists for each type of tree.

## Directory Structure
-----------------

The directory structure for the project data is organized as follows:

```
...
├── 08/
│ ├── triads.edges
│ ├── core_trees.edges
│ └── trees.edges
├── 09/
│ ├── triads.edges
│ ├── core_trees.edges
│ └── trees.edges
├── 10/
│ ├── triads.edges
│ ├── core_trees.edges
│ └── trees.edges
└── ...
```


There is a subdirectory for each number of vertices from 1 to 22. Within each
vertex subdirectory, there are text files that contain the orientation
data for the corresponding type of tree. 

For example, the `core_triads.edges` file in the `08/` directory contains the
orientation data for all core triads with 8 vertices.

## Contributing
-----------------

Contributions to the project data are welcome. If you have generated new data,
please submit a pull request to add the data to the appropriate directory.
Please ensure that the data is formatted as described in this README file, and
that the file names are consistent with the naming convention.
