# Treap
Java pseudo-code algorithm to built a Treap.


The goal of this repos is to create a Java pseudo-code algorithm to built a Treap.

A treap is a binary tree made of nodes. Each nodes consists of Key and Priority. 
The treap has to follow the rules of a BST for the Key of each node and the rules of a MaxHeap for the Priority of each node. 

The algorithm to build a treap, given an array of nodes, should be: 

1. By priority, sort the nodes in ascending order.  

2. By key, add the nodes to an empty BST from last node in the array (should be highest priority) to first element. 
