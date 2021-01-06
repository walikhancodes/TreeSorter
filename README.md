TreeSorter - 

Focuses on looking at two different strategies for maintaining the binary search tree:
 - Using a self-balancing binary search tree.
 - Inserting keys in a random order without rebalancing. (RandomizedTreeSet)

and two strategies for extracting the elements in sorted order:

 - Thinking of a binary search tree as a priority queue and repeatedly calling removeMin().
 - Using an in-order traversal of the tree.

Edited TreeSet.java so that it implemented the PriorityQueue interface. Then, adapted a self-balancing binary search tree (AVL) in Self-BalancingTreeSet.java. Finally, coded up the two approaches for extracting elements in TreeSorter.java (an inOrder( ) method is already implemented in TreeSet.java). In the same file, wrote a tester method that compares the four approaches on a large randomly shuffled list (e.g., of 2,000,000 elements).
