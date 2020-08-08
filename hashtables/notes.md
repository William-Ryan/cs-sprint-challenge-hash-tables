    1. Hashing functions - A hash function is a function where the input is any data, and the output is a number.
    
    2. Collision resolution - When a hash function maps two different keys to the same table address, that is a collision. Python uses Chaining to mitigate this in the form of Linked Lists.

    3. Performance of basic hash table operations - Insert = O(1), Delete = O(1), and Search = O(1) are the basic hash table operations in the worst case O(n).

    4. Load factor - Load factor is the Number of Items in the Hash Table divided by the total number of slots.

    5. Automatic resizing - If load factor goes over 70% ( 0.7 ) auto resizing would be the act of increasing/decreasing the hash tables length to provide better collision resolution as well as effecting the performance.

    6. Various use cases for hash tables
        - Search for elements within a large data set.
        - Find duplicate elements in a data set.
        - Quickly store and retrieve elements from a large data set.