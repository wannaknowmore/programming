# Data Structure

## What is it?
A collection of data values, the relationships among them, and the operations that can be applied to the data.

The most common data structres are: Link List, array, Binary Tree, Record/Object.
They come in different flavors and implementations.

## Data Structures and Objects
In the context of [OOP](https://en.wikipedia.org/wiki/Object-oriented_programming) **implementation**,
it is sometime useful to differentiate between a custom *data structure* and an *object*.
In this regard, a data structure contains only data with no behaviour while the object has behaviour (i.e. it has
methods that operate on the data).

This differentiation is a bit confusing with the original definition of the data structure. One is a logical definition
and the later comparison to an object is an implementation detail. When translating the logic to code, differentiating
between the pure data structure and an object with behaviour is useful.

Example: When implementing a link list, usually it is constructed from a collection of *Node*s which are pure data
structures and a *List* object that chains nodes to construct a linked list.
The List object has behaviour (adding, removing, searching).
