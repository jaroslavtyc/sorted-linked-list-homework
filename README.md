# Goal

## Implementation of Sorted Linked List

_Just another of many already existing and probably
better [Sorted Linked List implementations](https://github.com/search?q=sortedlinkedlist&type=repositories)._

This is proof of my know-how. Use at your own risk.

## Hint

PHP is great tool, but if you need to use optimized data structures, other than just hashmap (PHP array) or PHP objects,
**I strongly recommend you to use another programming language**.

For
example [Sorted Linked List has great implementation in <img src="./media/Rust_programming_language_black_logo.svg" data-canonical-src="./media/Rust_programming_language_black_logo.svg" width="15" height="15" /> Rust language](https://docs.rs/heapless/latest/heapless/sorted_linked_list/index.html)

Also do not forget that there are many structures,
like [B-Tree (balanced tree)](https://www.geeksforgeeks.org/introduction-of-b-tree-2/) and search techniques
like [Tree traversal](https://www.geeksforgeeks.org/tree-traversals-inorder-preorder-and-postorder/). Choose what suites
your need most.

# Application

_There are many ways, how to sort data. With increasing data size and demand of speed a
simple [PHP array sort](https://www.php.net/manual/en/array.sorting.php) became insufficient._

## Structure

Sorted Linked List keeps **non-unique** data in a sequence, **sorted** by their values, by **various comparing**
algorithms.

## Advantage

Its main advantage is very **small memory** footprint to sort data, even on very large data set and even during change of the
data set.

## Time Complexity

Time complexity to **sort** data is `O(n)` (linear), where n is the number of items in the list.

Time complexity to insert new value is `O(1)`, if you already know the position for new value. Otherwise `O(n)` (search
for position) + `O(1)` (insert new value).

