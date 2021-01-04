TreeSorter - 

We will look at two different strategies for maintaining the binary search tree:
 - Using a self-balancing binary search tree.
 - Inserting keys in a random order without rebalancing. (RandomizedTreeSet)

and two strategies for extracting the elements in sorted order:

 - Thinking of a binary search tree as a priority queue and repeatedly calling removeMin().
 - Using an in-order traversal of the tree.

Edit TreeSet.java so that it implements the PriorityQueue interface. Then, adapt any self-balancing binary search tree (AVL, splay, red-black) in Self-BalancingTreeSet.java. Finally, code up the two approaches for extracting elements in TreeSorter.java (an inOrder( ) method is already implemented in TreeSet.java). In the same file, write a tester method that compares the four approaches on a large randomly shuffled list (e.g., of 2,000,000 elements).
