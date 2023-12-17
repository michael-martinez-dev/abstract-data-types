# Abstract Data Types (ADTs) Overview

This repository contains implementations of various Abstract Data Types (ADTs)
in multiple programming languages. Each ADT is implemented with a focus on
understanding its structure, operations, and applications.

## Linked List

A linked list is a linear collection of data elements, where each element
points to the next. It's a dynamic data structure, meaning it can grow and
shrink at runtime.

### Use Cases

Suitable for applications with unpredictable data growth.
Frequently used in symbol table implementations.

### Pros

- Dynamic size.
- Efficient insertion/deletion at any position.

### Cons

- No random access. Sequential access is slower compared to arrays.
- Extra memory for pointers.

### Basic Operations

- [ ] Initialize the list.
- [ ] Insert an item.
- [ ] Check if the list is empty.
- [ ] Print the list.
- [ ] Find the length of the list.
- [ ] Destroy the list.
- [ ] Retrieve info from nodes.
- [ ] Search for an item.
- [ ] Insert an item.
- [ ] Delete an item.
- [ ] Copy the list.

## Stack

A stack is a collection of elements with two principal operations: push (add)
and pop (remove). It's a LIFO (Last In, First Out) structure.

### Use Cases

- Used in undo mechanisms in software.
- Essential for algorithm implementations like depth-first search.

### Pros

- Simple and fast operations.
- Easy to implement.

### Cons

- Limited access (only top element accessible).
- Not suitable for access-type applications.

### Basic Operations

- [ ] Push an item.
- [ ] Pop an item.
- [ ] Peek at the top item.
- [ ] Check if the stack is empty.
- [ ] Get the size of the stack.

## Queue

A queue is a collection that holds elements in a FIFO (First In, First Out)
manner.

### Use Cases

- Widely used in scheduling algorithms.
- Handling of real-time systems like traffic management.

### Pros

- Fair processing order (FIFO).
- Scalable for large data volumes.

### Cons

- Fixed capacity can limit size (in array implementations).
- Inefficient in some implementations due to shifting elements.

### Basic Operations

- [ ] Enqueue an item.
- [ ] Dequeue an item.
- [ ] Peek at the front item.
- [ ] Check if the queue is empty.
- [ ] Get the size of the queue.

## Tree

Trees are hierarchical structures with a single root and nodes with zero or
more children. Binary trees and BSTs (Binary Search Trees) are common types.

### Use Cases

- Hierarchical data representation (e.g., file systems).
- Efficient searching and sorting (BSTs).

### Pros

- Reflects structural relationships.
- Efficient searching, insertion, and deletion (in BSTs).

### Cons

- Complex structure.
- Can become unbalanced.

### Basic Operations

- [ ] Insert a node.
- [ ] Delete a node.
- [ ] Search for a value.
- [ ] Traverse the tree (in-order, pre-order, post-order).

## Graph

A graph is a set of nodes connected by edges. It can be directed or undirected.

### Use Cases

- Modeling networks (like social networks, city maps).
- Pathfinding algorithms (e.g., GPS navigation).

### Pros

- Represents complex relationships.
- Flexible structure.

### Cons

- Can be memory-intensive.
- Algorithms can be complex and computationally intensive.

### Basic Operations

- [ ] Add a vertex.
- [ ] Add an edge.
- [ ] Find adjacent vertices.
- [ ] Perform graph traversal (BFS, DFS).

This README can serve as a quick reference guide and a starting point for anyone
looking to understand or use these ADTs in their projects.