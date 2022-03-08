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
