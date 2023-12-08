# tree_inventory
The tree_inventory Python program/package provides a means of calculating a checksum for a directory tree and subtrees.  The checksums are stored in a .json file at the root of the tree and contains checksum information for each directory in the tree as well as a checksum of all file contents within each directory.  This information facilitates rapid difference examination between two copies of the tree, including a detailed listing of the specific subdirectory where differences can be found.  Each filename is part of the checksum process, such that adding, removing, or renaming a file is sufficient to flag a difference between two copies of the tree.  The tree_inventory program includes a comparison tool that can quickly show differences between two similar trees after having the checksum calculated on each.  An update-copy functionality is also provided.

The tree_inventory provides a command-line interface.  For information, use --help.  The package provides a number of functions that are similar to the CLI options provided.
