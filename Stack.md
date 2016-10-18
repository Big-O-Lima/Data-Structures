
_slides available [here](Source/Slides/Stack.html)_

#STACK
by Jose Torres [@CoderPug](http://www.github.com/coderpug)

##Concepts
- ADT Abstract Data Type
- Flexible size ( don't have to pre allocate memory, just add as you go ) ( When implemented with linked lists ) 
- LIFO scheme for insertion and deletion ( Last In First Out )

##Operations
- Push(:object) - inserts element at top
- Pop() - remove element at top
- Auxiliary 
  - top() - returns last element without removing it
  - size() - returns number of elements stored
  - isEmpty() - returns boolean

##Representation
- When using Linked List is composed as :
  - Node: { data, next< Node > }
  - Stack: { pointerTop< Node > , func... }

##Complexity
- Push : O(1)
- Pop : O(1)
- Top/Peek : O(1)

##Direct Applications
- Page visited web history
- Undo sequence in editor
- HTML Tag matching
- ...

##Problems

- Hackerrank: Cracking the Coding <https://www.hackerrank.com/challenges/ctci-balanced-brackets>
- Hackerrank: Stacks <https://www.hackerrank.com/domains/data-structures/stacks>

##Bibliography

- <https://en.wikipedia.org/wiki/List_of_data_structures>
- <http://coltech.vnu.edu.vn/~hieulq/ctdlgt/Lec04_StacksQueues.pdf>
- <http://www.knowstack.com/stack-queue-implementation-in-objective-c/>
