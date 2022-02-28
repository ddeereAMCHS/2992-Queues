# Queues

- Create a Queue class that will hold Integers
  - You need to determine how you will store the underlying data
  - Implement the constructor
  - Implement the enqueue method
  - Implement the dequeue method
  - Implement the front method
  - Implement the rear method
  - Implement the size method
  - Implement the isEmpty method
    - Do not use an isEmpty method for an underlying data structure
  - Implement a toString method that returns the queue with the front of the queue as the first element
    - Separate the elements with commas and surround all the elements with square brackets
- Create a program called `QueueTester.java`
  - Create a Queue object that will hold Integers
  - Prompt the user for a filename
  - Each line in the file will be a queue operation or the print command
    - For enqueue and dequeue operations, do not print anything
    - For front, rear, size, and isEmpty operations, print what is returned
    - For print operations, print the queue
  - You must read in the line and perform the specified operation on the Queue object you created

***Example Input:***\
input1.txt\
***Example Contents of input1.txt:***\
enqueue 7\
enqueue 12\
print\
enqueue 19\
enqueue 37\
print\
dequeue\
print\
front\
rear\
size\
isEmpty\
enqueue 72\
print\
dequeue\
dequeue\
dequeue\
print\
front\
rear\
size\
isEmpty\
dequeue\
print\
front\
rear\
size\
isEmpty\
***Example Output:***\
[7, 12]\
[7, 12, 19, 37]\
[12, 19, 37]\
12\
37\
3\
false\
[12, 19, 37, 72]\
[72]\
72\
72\
1\
false\
[]\
null\
null\
0\
true
- - - - - - - - - - - -

## Extra Credit

- Implement the front, rear, size, and isEmpty methods using only the enqueue and dequeue methods
  - Don't use any methods from the underlying data structure
