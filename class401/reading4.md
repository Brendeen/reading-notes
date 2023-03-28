# Class 4

[Back to home page](../README.md)

## Classes and Objects

Q. What are the key differences between classes and objects in Python, and how are they used to create and manage instances of a class?

- Some key differences between classes and objects are:

  1. Can only define single classes, but many objects
  2. Classes are what determine how an object will act/ is a blueprint for an object.
  3. Objects take up memory space, while classes dont.

  The overall main difference between a class and an object is that a class is what encapsulates an objects data, while an object is an instance of the class its under, with its own values. For example, you could have a class that is called "Super_Heros", and under the class there are objects like "Spider-man" and "Wolverine".

## Thinking recursively

Q. Explain the concept of recursion and provide an example of how it can be used to solve a problem in Python. What are some best practices to follow when implementing a recursive function?

- Using recursion is identifying a problem, and making it simpler. This could also be making a solution for a problem. The idea behind it is looking over your problem, and breaking it down to be easier to fix. A good example of this in python could be taking a bunch of complex code and refactoring it or using methods instead of extra lines of code. When using recursive functions, you always start with the base case and the recursive case. The base case is what will stop the function, while the recursive case is what will call the function. When using a recursive function, make sure it doesnt call itself forever (making an infinite loop).

## Pytest fixtures and coverage

Q. What is the purpose of pytest fixtures and code coverage in testing Python code? Explain how they can be used together to improve the quality and maintainability of a project.

- Fixtures are used to manage our applications dependancies. They are primarily used for testing a wide range of values and data types in testing.
- Code coverage is a measure of how much coverage there is for your program. It monitors things like executed code/functions, and is usually used to see how effective your tests are.

## Bookmark and review

- [Pytest Fixtures](https://docs.pytest.org/en/latest/fixture.html)

## Things I want to know more about

What are some common examples of recursion in the industry? Or what would a company use recursion for on their app?
