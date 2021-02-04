# JP-Morgan-Virtual-Experience
This repository contains all the submitted patch files of the various tasks assigned by JPMorgan Chase & Co. Software Engineering Virtual Internship

---
## I have worked on the following tasks during the internship
#### 1. Interface with a stock price data feed 

Interface with a stock price data feed and set your system for analysis of finalcial data using Python 3
Unit tests are little snippets that run independently from the main application and help us to catch errors early on to make sure our code outputs the results that we desire.
A useful pattern for unit testing is:
- We first **build** simulated test scenarios with dummy data to test
- Then we make operations and call the method we want to **act** on
- Finally we check if the output was expected

Unit tests mostly use dummy data to represent the test cases we pass into methods and the expected outcome of these methods when such test cases are given. 

Some best practices to remember are:

- Only use one assertion per test
- Build independent test cases, they should work in case of any changes on the software
- Use clear naming conventions
- Having a "test as your code" approach