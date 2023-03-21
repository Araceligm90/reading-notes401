# Reading Notes 2

**1. What is TDD?**

TDD or Test-Driven Development is a strategy that consists on writing the tests first, then move onto writing the code to then refactor it accordingly.

By following this strategy the developer will produce a more robust and secure code, besides producing it faster.


**2. What does the 'if__name__=="__main__":' do?**

Before executing any code, the Python interpreter reads the source files and defines special or global variables.

If the Python interpreter runs the source file module as the main one, the name will be set to 'main'. For any other imported modules, the name will be set to the actual name of the module.

This way it is easy to identify which module is the standalone or main one, and which ones are secondary.


**3. What is recursion?**

Recursion is the process in which a function calls itself directly or inderectly.
A recursive function solves a particular problem by calling a copy of itself and solving smaller subproblems of the original big problem.

Because a recursive function calls itself, it is easy to write a function incorrectly that ends up in an infinite loop. That is why every recursive function has two parts: the base case (function doesn't call itself) and the recursive case (function calls itself). The latter is what will keep happening if the base case hasn't been reached.



