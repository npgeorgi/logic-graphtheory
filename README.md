Logic-Graph Theory
==================

This set of Mathematica notebooks contains implementations of finite set theory,
first order logic, and graph theory.

In the packages for finite set theory, the ZF axioms are used.

In the packages for first order logic, basic elements of model theory are
presented.

The graph theory is presented in the packages containing the ZF axioms.

There are two pairs of Mathematica packages:

  1. "``ZFfinite`Master9` ``" & "``Combinatorics`MasterC9` ``".
  2. "``ZFfinite`Master` ``" & "``Combinatorics`Master` ``".

The first pair does not use the Combinatorica Mathematica package,
while the second one does.

The new approach in the presentation of graph theory, is that it allows graph
edges that pass through several vertices, instead of the usual two. This
extended approach, fits elegantly in applications of graph theory, for example in
flight planning, or similar problems.  
This approach allows also the visualization of hypergraphs.

This set of notebooks require Mathematica 10.3 or later.

Start by opening the file `LoadingOneOfTwoPairsOfPackages.nb`, which contains
instructions for setting up all the requirements to use the rest of the
Mathematica notebooks.

Note that all outputs are shown, except the ones which use as input Manipulate,
or similar constructs; the reason is that when the dynamic updating is enabled,
as it should be, the outputs may cause issues. So after evaluation of these
cells, delete the result to avoid problems.

Download
--------
Due to size concerns, the git repository does not currently contain the
mathematica notebooks of this project. To download them, go to the releases
page and pick the latest release available.
