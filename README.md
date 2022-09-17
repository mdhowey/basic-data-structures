# Basic Data Structures
- This is a place for me to take notes on data structures as I am learning about them. I will also use this as a place I try to implement the data structures. I will follow OOP principles and attempt to immplement these using classes as much as possible. 

- Since this will be a place for me to take notes, I will update this repo regularly as I learn about new data structures.

## Lists
- Defined as a finite, ordered sequence of data items --> elements
  - Ordered means that each element has a position within the list
- Empty lists contain 0 elements
- Length is defined as the number of elements in a list 
- Beginning of the list is referred to as the 'tail'
- End of the list is referred to as the 'head'
- Sorted refers to a list having its elements positioned in ascending order of value
- Unsorted refers to a list that has no particular relationship between elements

A list types inherit from the List class and are denoted by containing the word 'List' in the class name.

### Array
- Arrays are the most basic list implementation
- Arrays are fixed in size and cannot grow or shrink to accamodate more elements then with what it is initialized
- Array elements are indexed; element positions are available to the client

### Linked List
- Uses 'pointers' to point to the following value with the list
- Takes advantage of dynamic memory allocation --> unlike arrays, linked lists can grow and shrink in size dynamically
- 'Nodes' are the bbjects/elements with linked lists

The LinkedList class makes use of a Node class

### Doubly Linked List


### Stacks
- Defined as a list-like structure in which elements are inserted or removed from one end and one end only
- Follow LIFO policy: Last In, First Out --> elements are removed in reverse order of their arrival
- 'Top' refers to the accessible element of the stack
- Elements are 'pushed' onto the stack
- Elements are 'popped' from/off the stack

### Queues

## Dictionaries