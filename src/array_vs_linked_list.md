# Array vs Linked List

## Array
- Constant time - 0(1)
- Memory usage: fixed size


|Number | 2 | 4 | 6 | 5 |  - | - | - |
|----|---|---|---|---|  - | - | - |
|Position | 0 | 1 | 2 | 3 |  4 | 5 | 6 |
|Usage|u  | u | u | u | un | un | un|

Legend: u = used, un = unused
- 7 * 4 = 28 bytes
- Memory may not be available as one large blcok
- Inserting an element
  - At beginning = O(n)
  - At end = O(1) - if the array is not full, O(n) - array full
  - At mid = O(n)

## Linked List
- O(n)
- Memory usage: 
   - no unused memory 
   - extra memory for pointer variables

```
      | 2 | - | -> | 4 | - | -> | 6 | - | -> | 5 | - |
        ^                ^        ^                ^
       Head           Pointer   Value             Tail
```
- 8 * 4 = 32 bytes
- Memory may be available as multiple small blocks
- Inserting an element
  - At beginning = O(1)
  - At end = O(n)
  - At mid = O(n)
