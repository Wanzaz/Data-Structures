# Linked List - Implementation in C/C++

```
              10             20            30            40
   |10| -> | 2 | 20 | -> | 4 | 30 | -> | 6 | 40 | -> | 5 | 0 |
    ^                      ^                 ^             ^
   Node*                  Data              Link          Node*
```


### C
```c
Struct Node
{
    int data;
    Struct Node* link;
}

Node* A;
A = NULL; //empty list
Node* temp = 
    (Node*)malloc(sizeof(node)) //dynamically alocated memory
    (*temp).data = 2;
    (*temp).link = NULL;
    A = temp;
```

### C++
```c++
Struct Node
{
    int data;
    Node* link;
}

Node* A;
A = NULL; //empty list
Node* temp = new Node();
temp -> data = 2;
temp -> link = NULL;
A = temp;

temp = new Node();
temp -> data = 4;
temp -> link = NULL;

//Traversal
Node* temp1 = A;
while(temp1 -> link ! = NULL)
{
    temp1 = temp1 -> link;
}

temp1 -> link = temp;

```
