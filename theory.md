# 1

## Introduction to Datta Structures

- A data sturcture is a way to store and organize data in a computer, so that it can be used efficiently
 
- We talk about data-structures as:

 1) Mathematical/logical models or Abstract data types
    
 2) Implementation


## List [ADT]

- Store a given number of elements

- Read elements by posiotion

- Modify element at a position

Arrays [Concrete Implementation]


## Linked List

##### Abstract data types [ADTs]

- Define data and operations, but no implementation.

-Arrays, Linked List, Stack, Queue, Tree, Graph...
    
1)Logical view

2)Operations

3)Cost of operations

4)Implementation


# 2

## List [ADT]

- Store a given number of elements of a given data-type

- Write/modify element at a posiotion

- Read element at a position

- Empty list has size 0

- Insert, remove, count

1)Access - Read/Write element at an index = constant time O(1)

2)Insert - linear time O(n)

3)Remove - linear time O(n)

4)Add - 0(n)


# 3

## Linked List

    Struct Node
    {
        int data; //4 bytes
        Node* next; //4 bytes
    }
  
- First element of the node is head note

- Address of the head node gives us access of the complete list

- a element always has the value and the point the sequal position of the next value

- the last element in linked list has pointer value of 0


#### Example of the linked list:

    5 | 12  -> 4 | 24 -> 2 | 0
    -in the first node the 5 = value, 12 = pointer on the second note position

- Access to elements = T n, O(n) - linear time
- Insertion = O(n) 
