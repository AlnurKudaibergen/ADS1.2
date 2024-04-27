# ADS1.2
# Custom Data Structures

This project implements custom data structures such as ArrayList and LinkedList along with logical data structures like Stack, Queue, and MinHeap.

## MyList Interface

The `MyList` interface represents a custom list data structure. It provides methods to add, get, and remove elements from the list, as well as obtain its size and iterate over its elements.

## MyArrayList Class

The `MyArrayList` class is an implementation of the `MyList` interface using an array-based list. It dynamically resizes its internal array to accommodate additional elements.

## MyLinkedList Class

The `MyLinkedList` class is an implementation of the `MyList` interface using a doubly linked list. It provides efficient insertion and removal operations at both ends of the list.

## MyStack Class

The `MyStack` class represents a stack data structure implemented using `MyArrayList`. It follows the Last In, First Out (LIFO) principle.

## MyQueue Class

The `MyQueue` class represents a queue data structure implemented using `MyLinkedList`. It follows the First In, First Out (FIFO) principle.

## MyMinHeap Class

The `MyMinHeap` class represents a min-heap data structure implemented using `MyArrayList`. It maintains the heap property where the parent node is smaller than its children.
