[Home Page](https://devaoc.github.io/reading-notes/)

# Trees

## Common Terminology

- Node: This is an instance of a class which contains a value and a reference to another node.
- Root: The root is the node at the beginning of the tree.
- K: The number which specifies how many children a node can have in a k-ary tree. In a binary tree k=2.
- Left: A reference to one child node, in a binary tree.
- Right: A reference to the other child node, in a binary tree.
- Edge: The edge is the link between a parent and a child node.
- Leaf: A leaf is the node at the end of a branch. (Has no children)
- Height: The height of the tree is the amount of edges between the root and the furthest leaf.

## Traversals

There are two types of traversals:

- Depth (Height): In a depth traversal we prioritize traversing the height of the tree first.
- Breadth (Width): Traversing through a tree by its width allows you to read it like a book.

The most common way to traverse a tree is to use recursion.
