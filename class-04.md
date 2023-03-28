# READING NOTES 4


## Classes and Objects


**1. What are the key differences between classes and objects in Python, and how are they used to create and manage 
instances of a class?**

An object is a data structure that contains data (attributes) and functions that operate on the data. An object is an 
instance of a class, and each object has its own set of attributes and methods.

A class, on the other hand, is a blueprint for creating objects. It defines the attributes and methods that each object 
of the class will have. Inside a class definition you can define attributes and methods that will be shared by all 
objects of that class. 


**2. Explain the concept of recursion and provide an example of how it can be used to solve a problem in Python. 
What are some best practices to follow when implementing a recursive function?**

Recursion is a technique thar involves a function calling itself repeatedly until a specific condition is met. 
Recursion solves a problem by braking it down into smaller sub-problems and solving each of those sub-problems in a 
similar way until a base case is reached.

When implementing recursion it is important to set a base case and a recursive case. The base case will be in charge of 
terminating the recursion (and avoiding an infinite loop), while the recursive case will continue until the base 
case is reached.


**3. What is the purpose of pytest fixtures and code coverage in testing Python code? Explain how they can be used 
together to improve the quality and maintainability of a project.**

Pytest fixtures and code coverage are two important tools in Python. The first one can help make the testing code easier
to organize and can help clean up after tests are run. Code coverage is a way to measure how much of the code is being 
tested and can help identify places where there might be bugs. 



