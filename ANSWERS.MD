### What is the purpose of the various auxiliary methods populateList, populateFifoList, and ReverseLines.printReverse?

These methods help us solve problems that have recurring steps. The populateList and populateFifoList methods repeatedly add items to a list. The printReverse method prints each item in a stack. These recursive methods continue by calling itself until the base case is reached instead looping through each iteration.

### Why do these methods need to have arguments, and how does the argument change from one recursive call to the next?

Arguments have been used in these methods to continually break down the problem into smaller/next steps until the base case is reached as recursive call needs to be stopped when the current node is null for the populateList and populateFifo list methods. Similarly, in this task, the argument gets updated each call to reflect the next node or input value.

### What are the time and space complexity of each of the populateList populateFifoList methods, as well as ReverseLines.printReverse?

Complexities are as follows:

populateList is O(n)
populateFifoList is O(n)
ReverseLines.printReverse is O(n)

### Which of these methods can be implemented using while loops?

All methods can be implemented using while loops.

