# Homework 2 part 4.A

## arrays
### pros of arrays
- Use an existing index to access a particular piece of data quickly
- Use a jagged array can help to speed up the program and reduce the space of memory because data often has a different and even shape.
### cons of arrays
- Array searching is very slow for a large data
- Insert an new item to a large and full array can be very bad because the current array needs to move a bigger array
- Similar to insertion, delete an item from a large array can slow down the program

## lists
### pros of lists
- Insert an item to a doubly linkedlist takes O(1) time
### cons of lists
- Access,update,delete,and search: may take 
O(n) time because we need to traverse sequentially from the head to the end
- linkedlist has a slow, random access performance
## stacks and queues
### Pros of stacks
- first in and last out
- Stack is great for programs where you need to reverse things. Also good for keeping track of state as things are pushed on and popped off the stacks.
- Add/remove from back of the structure
### Cons of stacks
- not useful when to find an item in the middle of a stack
- not useful for sorting consistently
### Pros of queues
- first in and first out
- has a doublylinkedlist implementation that has O(1) when enqueuing and dequeuing
### Cons of queues
- not useful when pulling items from the middle

## hash-based data structures (Key-Values)
### Pros of hash-based structures
- Hash tables are excellent at managing many key-value pairs and volatile data
- Associative array is an abstract datatype, organize data in a specific way.
- Hash map operations always take the sum amount of time, regardless of the size of the hash table.
- Data and hash maps is stored in such a way that searching is much faster than many other data structures.
- Search, insertion and deletion are quick. All take O of one or constant time, because its runtime is consistent across any input.
### Cons of hash-based structures
- take up more spaces
- Hash functions are not reversible.
- Can not feed the hash value into another function and get the original data back.
- Collisions must handle with separate chaining, with create linked lists with additional values.
-Search, insertion and deletion may take up more time, and up to O of n if all the values are stored in one bucket.

## trees
### Pros of trees
- A binary search tree is often used to sort key value pairs.
- Binary search tree: maintain sorted order while staying fast for insertion, deletion, and accessing.
- Balance tree take O of log N time because every node encounter, eliminate another half of the tree
### Cons of trees
- deleting requires having to traverse the whole tree
- unbalance tree could take up to linear time



