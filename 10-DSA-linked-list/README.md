![cf](http://i.imgur.com/7v5ASc8.png) 10: Linked List
===

## Learning Objectives
* Students will be able to implement a singly linked list
* Students will be able create and implement common linked list methods

## Resources
* Watch [linked lists]
* Skim [linked list wiki]

## Outline
![linked-list](https://s3-us-west-2.amazonaws.com/slugbyte-assets/linked-list.svg)

### Singly Linked List
Singly linked lists contain a series of nodes where each node contains a `value` and a `next` property. The `next` property points to the next node in a line of interconnected nodes. The beginning of a linked list is often referred to as the *head*, whereas the end of the list is often referred to as the *tail*.  The *tail* can easily be identified as it's `next` property will hold a value of `null`, simply because there are no more nodes in the list. Standard operations that can be performed on a singly linked list include:
  * insertion (ie: `append` and `prepend` methods)
  * deletion (ie: `remove` method)
  * traversal (ie: `find` method)

[linked lists]: https://www.youtube.com/watch?v=njTh_OwMljA
[linked list wiki]: https://en.wikipedia.org/wiki/Linked_list
