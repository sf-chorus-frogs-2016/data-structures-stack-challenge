# Stacks

A stack is a special data structure where you only add, access, and remove elements from its top.  A stack is also known as a last-in first-out (LIFO) structure.

## Why is this important?

While you can use a list to act as a stack, sometimes its useful to have an object that has an explicit interface for just that purpose.

##Releases

###Release 0: Write tests

Write RSpec tests to specify the following _limited_ interface for a `Stack` class.

####Interface
- `new(suggested_capacity)` - Instantiate a new stack with an optional initial capacity
- `push(element)` - Add a new element to the top of the receiver
- `pop` - Remove the top element from the receiver
- `top` - Answers the top element of the receiver
- `empty?` - Answers whether or not the receiver is empty

Your design should enable stacks to grow if you try to add more elements than the current capacity.

###Release 1: Implement `Stack`

Implement your `Stack` class using your `FixedArray` class.

##Resources

* [Wikipedia: Stack (Abstract Data Type)](http://en.wikipedia.org/wiki/Stack_%28abstract_data_type%29)
* [Wikipedia: (Computing) Stacks](http://en.wikipedia.org/wiki/Stack#Computers)
