# CLASS 6 READING NOTES


## Ten Thousand Game 1


**1. How can the random module be utilized in Python to generate random numbers or make selections from a list, and 
what are some common functions available within the module?**

The Random Module is a built-in module that allows the user to do the following:

    a. randint(a, b): returns a random integer between a and b (including both).
    b. random(): returns a random number between 0 and 1 (1 not incluedd).
    c. choice(seq): returns a random element from a sequence (list, set, tuple, etc).
    d. shuffle(list): randomly shuffles the elements in a list.
    e. randrange(start, stop, step): generates a random integer within a range. 
    

**2. In the context of software development, what is risk analysis, and what are the key steps involved in conducting 
a risk analysis for a software project?**

In software development, risk analysis is the process of identifying the risks in applications or software being built
and focusing on testing them first. After this is done, the process of assigning the level of risk is done and after 
that the impact of the risk is calculated. 

To summarize, these are the three steps of risk analysis:

    a. Searching the risk
    b. Analyzing the impact of each individual risk
    c. Measures for the risk identified


**3. What is test coverage and why is it an important (or potentially misleading) metric in software testing?**

It refers to the percentage of cose the is being executed during the testing process. While it is useful for identifying
untested areas of code, high coverage numbers do not necessarily mean that the tests are effective or that the software
is free from defects. Therefore, the risk of focusing too much on test coverage is that it can lead to a false sense of 
security.
    

**4. What is Big O notation, and how is it used to describe the performance of an algorithm? Give an example of an 
everyday task (not software related) that demonstrates O(n) time complexity.**

Big O is a mathematical notation that describes the time complexity of an algorithm. It is important to test the 
efficiency of an algorithm. In simpler words, it tells us how long an algorithm takes to execute relative to its size. 

An everyday task that demonstrates the O(n) time complexity is folding your clean clothes. Folding one garment may take
30 seconds, but if you have 10 garments then it'll increase to 5 minutes, and if you have 20 it will increase to 10 
minutes.

