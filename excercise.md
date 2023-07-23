# Exercise

```c
##Exercise: linked_list_cycle
Allowed functions: None

You have been given a linked list. Even though it should be a standard 'next node' list, there's a bug that might make one of the nodes reference an earlier node in the chain and create a cycle.

Create a function `detect_cycle` which checks whether a cycle exists in the linked list passed to it. The function should return 1 if a cycle is detected and 0 if not. 

The linked list node is defined as follows:
```c
typedef struct node
{
    int value;
    struct node *next;
}Node;
```

Here’s how it should be prototyped :
`int detect_cycle(Node *head);` 

Hint: One possible solution involves using two pointers moving at different speeds.
```
# Submissions 
 git push your solution in this repo and hit /submit in Discord