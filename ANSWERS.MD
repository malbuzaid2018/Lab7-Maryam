### What is the purpose of the various auxiliary methods populateList, populateFifoList, and ReverseLines.printReverse?

Because LinkedStack does not require an explicit constructor since you have methods created in its class that you can call. Thus it eliminates the need for a constructor.

### Why do these methods need to have arguments, and how does the argument change from one recursive call to the next?

For LinkedStack methods the push, peek, and pop methods have a complexity of T(n) = O(1), and a space complexity of S(n) = 0(1); as they are in constant time. Whereas for the main class in ReverseLines the isEmpty and asList both have a time complexity of T(n) = O(1) and S(n) = O(1); they are in constant time.

### What are the time and space complexity of each of the populateList populateFifoList methods, as well as ReverseLines.printReverse?

We could have achieve that by using an arrayList as the container so that we have O(n).

### Which of these methods can be implemented using while loops?

Pros:
- Operating on constant time and space is also an advantage.
- Using push and pop methods will utilize less memory thus make them faster.

Cons:
- Returning whole stack at once means that each value is returned at once rather individually.
- Returning a large stack will take time.

