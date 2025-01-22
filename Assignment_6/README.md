Click the following link to Github classroom to clone the starter repository for assignment. Work directly from the sheridan-python organization.

https://github.com/puja0902/Assignment-6
Assignment: A Fibonacci series iterable

Write an iterable which produces an iterator of the Fibonacci series for a given value.

Example:

(/7) Structure & naming

    (/1) Write a test module called test_fibonacci.py
    (/1) Write a module called fibonacci.py
    (/5) Create an iterable class called Fibonacci which requires a single positional argument. Remember, an iterable class has to:
        Have an __iter__
        Have a __next__
        Raise a StopIteration exception when there are no more items

Requirements & build steps

Using TDD methodology, develop an algorithm to assert the following test cases.

Note: iterables return iterators and not lists, so to build a proper assertion, cast the result as a list.

    If constructed with a value other than an integer, the Fibonacci constructor should raise a ValueError.
    Given a constructor value of 0, the iterator should produce the values [0] if cast as a list.
    Given a constructor value of 1, the iterator should produce the values [0, 1] if cast as a list.
    Given a constructor value of 2, the iterator should produce the values [0, 1, 1].
    Given a value of 4, the iterator should produce [0, 1, 1, 2, 3]
    Given a value of 10, the iterator should produce [0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55]
    Given a negative value, the iterator should produce an empty list.

Note: Any integer must be accepted and calculate a correct Fibonacci sequence. Building a function which only handles the above cases is insufficient and will not be accepted.
(/21) Development matrix
Step 	Test assertion 	Code written to pass 	Commit Exists
#1 			
#2 			
#3 			
#4 			
#5 			
#6 			
#7 			
Code style

Tests & codestyle must pass. -1% will be deducted for each code style violation.

The course grading policy is available here: Evaluation Plan & Grading Policy.