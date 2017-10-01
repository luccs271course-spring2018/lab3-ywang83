# Questions & Answers

##`TestIterator` Questions
### TODO also try with a LinkedList - does it make any difference?
To use a Linkedlist does not affect the test functions, but the performance of each test is varied. 

For `testEmpty` and `testAverageBalues` seem faster with ArrayList, while `testRemove` and `testNonempty` perform better with Linkedlist.

### TODO what happens if you use list.remove(77)?
It will throw an `OutOfBoundException` as `java.lang.IndexOutOfBoundsException: Index: 77, Size: 7`.

##`TestList` Questions
### TODO also try with a LinkedList - does it make any difference?
The Linkedlist still does not affect the functions but the performance of some of the tests.

Some of the tests with ArrayList perform better than those with LinkedList, such as `testSet`, `testAddMultiple2`, `testRemoveObject` and `testSubList`. Others does not show much differences.
