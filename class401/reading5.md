# Class 5

[Back to home page](../README.md)

## Linked lists

Node, a data structure that stores a collection of value, and points to another node. Each node has 2 parts, the data, and a pointer to the next node.

The first node is refered to as the root node, or head, with the last node having a None value for next.

simple example:
class Node:

    def __init__(self, value=None, next=None):
        self.value = value
        self.next = next

Linked lists are a one way, meaning you can only go left to right. You can use the .next command to iterate through your list.

## Bookmark

- [Big O: Analysis of Algorithm Efficiency](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)
