# ArrayPartitioner
A simple class that splits a array into several small arrays of the given max size

To use
------
* Import the jar
* Call the ArrayPartitioner's partition method with the array to be split and the maximum length at which it needs to be split

eg
partition([1,2,3,4,5], 2) ==>: [ [1,2], [3,4], [5] ]
partition([1,2,3,4,5], 3) ==>: [ [1,2,3], [4,5] ]
partition([1,2,3,4,5], 1) ==>: [ [1], [2], [3], [4], [5] ]
