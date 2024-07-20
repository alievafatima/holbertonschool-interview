Write a function that inserts a value into a Max Binary Heap:

Prototype: heap_t *heap_insert(heap_t **root, int value);
root is a double pointer to the root node of the Heap
value is the value to store in the node to be inserted
Your function must return a pointer to the inserted node, or NULL on failure
If the address stored in root is NULL, the created node must become the root node.
You have to respect a Max Heap ordering
You are allowed to have up to 6 functions in your file