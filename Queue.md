_slides available [here](http://htmlpreview.github.io/?https://github.com/Big-O-Lima/Data-Structures/blob/master/Source/Slides/Queue.html)_

#QUEUE
by Jose Torres [@CoderPug](http://www.github.com/coderpug)

##Concepts
- ADT Abstract Data Type
- Flexible size ( don't have to pre allocate memory, just add as you go ) ( When implemented with linked lists ) 
- FIFO scheme ( First In First Out )

##Operations
- Enqueue(:object) - inserts element at the tail (end)
- Dequeue() - remove and returns element at the head (front)
- Auxiliary 
  - front() - returns element in head without removing it
  - size() - returns number of elements stored
  - isEmpty() - returns boolean

##Representation
- When using Linked List is composed as :
  - Node: { data, next< Node > }
  - Queue: { pointerHead< Node >, pointerTail< Node > , funcs... }

##Complexity
- Insert : O(1)
- Remove : O(1)
- Front: O(1)
- Size : O(1)

##Direct Applications
- Round Robin Schedulers <https://en.wikipedia.org/wiki/Round-robin_scheduling>

##Problems

- Hackerrank: Cracking the Coding <https://www.hackerrank.com/challenges/ctci-queue-using-two-stacks>
- Hackerrank: Queues <https://www.hackerrank.com/domains/data-structures/queues/difficulty/all/page/1>

##Bibliography

- <https://en.wikipedia.org/wiki/List_of_data_structures>
- <http://coltech.vnu.edu.vn/~hieulq/ctdlgt/Lec04_StacksQueues.pdf>
- <http://www.knowstack.com/stack-queue-implementation-in-objective-c/>
