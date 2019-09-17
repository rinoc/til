# Traversing the own keys of an object

In ES6, the traversal order of an objects own keys is predictable.

> Property keys are traversed in the following order:
> 
> - First, the keys that are integer indices (what these are is explained later), in ascending numeric order.
> - Then, all other string keys, in the order in which they were added to the object.
> - Lastly, all symbol keys, in the order in which they were added to the object.

from here: https://2ality.com/2015/10/property-traversal-order-es6.html#traversing-the-own-keys-of-an-object
