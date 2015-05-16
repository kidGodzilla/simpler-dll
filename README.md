# simpler-dll
A concise, code golfed doubly-linked list object
277 characters

Each node contains a value and up to two objects, representing the previous (p) and next (n) object in the list, if applicable.

```
@property {object}  d [data]    represents the doubly-linked list
@property {number}  l [length]  represents the total length of the list
@method             a [append]  appends a new node to the list, e.g. d.a('first')
@method             c [clone]   clones a node at a specific position and appends it to
                                    the list, e.g. d.c(3)
   
@method             e [erase]   erases the entire list
@method             r [remove]  removes a specific node from the list, e.g. d.r(3)
@method             A [toArray] returns the list as an array of values
```
