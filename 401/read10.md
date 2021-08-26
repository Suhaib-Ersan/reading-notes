# Stacks and Queues

Stacks are similar to linked lists, but are less complex.    
They are similar structure of nodes that each references the next one in the list or stack, the difference here is that linked lists can also reference the previous node.
They also share having a "head", which is the first item in the list and is usually the starting point (in the stacks it's always the starting point).
Stacks generally have a few methods, like:
- pop, which will remove the head of the stack.
- push, which will add a new node to the stack, in place of the head.
- peek, which will return the first node, which is the head.

Because of stacks limitations and less complexity, they follow a rule called FILO `First In Last Out` or LIFO `Last In First Out`, both meaning the same thing: that the head is what always gets popped and you always start at the head, and that any new nodes will be "higher" than the old head.



[Go back to table of contents](https://suhaib-ersan.github.io/reading-notes/) 