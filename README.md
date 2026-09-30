# Binary Tree Maximum Depth

## Problem Statement

Given the root of a binary tree, find its maximum depth.

The maximum depth is the number of nodes along the longest path from the root node to a leaf node.

## Example

        1
       / \
      2   3
     /
    4

Longest path:

1 → 2 → 4

Output:

Maximum Depth: 3

## Approach

Use recursion.

For every node:

1. Find the maximum depth of the left subtree.
2. Find the maximum depth of the right subtree.
3. Take the larger depth.
4. Add `1` for the current node.

If the node is `null`, its depth is `0`.

## Complexity

- Time: O(n)
- Space: O(h)

Where:
- `n` = number of nodes
- `h` = height of the tree

## Concepts Practiced

- Binary Trees
- Tree Depth
- Recursion
- DFS
- Postorder Traversal