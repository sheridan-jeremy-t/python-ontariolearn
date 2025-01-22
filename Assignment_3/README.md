Follow the link to GitHub classroom to fetch the assignment. A new repository will be created for you under the sheridan-python Github organization with your username appended to it. Clone this repository. 

https://github.com/puja0902/Prime-Factor-Fall-2024

Submission:

    When complete copy & paste the link to your repository here.
    The tests MUST pass (both locally when you run pytest), and by GitHub Actions (the test runner). Code styling is enforced. To run locally, run pylint **/*.py

To view the status of your tests, go to your repo in a browser . 

Each time you push to GitHub, the tests will run.

When tests have successfully passed, a green checkmark will appear else failures are indicated using a red x.

If it's Red X click on it and check details and find out errors.

To view the commit history, click on the "commits" link.



Assignment: Prime Factors

In this assignment, you will build an algorithm that will generate a list of the prime factors for a given number.

Prime factors (also known as prime numbers or a prime) are numbers which cannot be formed as the result of a multiplication (https://en.wikipedia.org/wiki/Prime_number).

Using the Three Rules of TDD, develop the algorithm based on each assertion listed below. After each step commit your work using git commit.
Completing the assignment

There are 8 steps to complete. For each step, the following is expected:

    A test to be written with the specified assertion before any code is written.
    Only enough code is written to make the test pass.
    A git commit exists for each step

Evaluation

This assignment is marked out of 30.
Points 	Description
24 	Functionality (see matrix)
0.5 	Clone the repository
0.5 	The tests MUST pass (both locally when you run pytest), and by GitHub Actions (the test runner).
5 	Code style (-1 per reported linting error)
30 	Total

There are 8 steps to this assignment. Each step is worth 3 points for a total of 24 points.

Note: The function your write must calculate prime factors for any number given. It is not enough to return the expected values using if statements and will be considered incomplete / not accepted.
Evaluation Matrix
Step 	Test assertion 	Code to pass 	Commit Exists
#1 			
#2 			
#3 			
#4 			
#5 			
#6 			
#7 			
#8 			
Requirements

Write a function called generate_prime_factors in the module prime.py. This function will accept an integer as an argument, and return a list of integers.

E.g.

Step 1:

Write a test that asserts that when generate_prime_factors is called with a data type that is not an integer (e.g. a string or float), a ValueError is raised. Write the appropriate code to solve this and then commit the changes.

Step 2:

Write a test that asserts that when generate_prime_factors is called with 1, an empty list is returned. Solve & commit.

Step 3:

Write a test that asserts that when generate_prime_factors is called with 2, the list [2] is returned. Solve & commit.

Step 4:

Write a test that asserts that when generate_prime_factors is called with 3, the list [3] is returned. Solve & commit.

Step 5:

Write a test that asserts that when generate_prime_factors is called with 4, the list [2, 2] is returned. Solve & commit.

Step 6:

Write a test that asserts that when generate_prime_factors is called with 6, the list [2, 3] is returned. Solve & commit.

Step 7:

Write a test that asserts that when generate_prime_factors is called with 8, the list [2, 2, 2] is returned. Solve & commit.

Step 8:

Write a test that asserts that when generate_prime_factors is called with 9, the list [3, 3] is returned. Solve & commit.