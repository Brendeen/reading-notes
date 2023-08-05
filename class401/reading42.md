# Class 42

[Back to home page](../README.md)

## Ethics in tech

The article I read about was: [The code I’m still ashamed of](https://medium.freecodecamp.org/the-code-im-still-ashamed-of-e4c021dff55e)

This author talks about his early career in the coding world in the early 2000s. To sum up the article, he had started coding very early on, and his dad got him a part time job when he was 15. He got little money, but great work experience. After awhile when he was in his 20s he got his first job at marketing firm in Toronto Canada makinf marketing websites for pharmacutical companys. On the serface it seemed like a good gig, getting good money and coding out some simple interactive websites. Hoowever, one of the websites he was making had a quiz that was under the serface very unethical. The website and quiz was targeted at younger women, and it would give them a quiz to help them find which treatment was right for them. But what was really going on is the quiz would always point to the same advertisement to a specific drug, no matter what the user put in (unless they said they had an allergy). The author describes how he even felt it was wrong when he wrote it but didnt want to question the company. He eventually learned that the drug had huge side effects of suicidal thoughts and depression. HEaring about this and even about a girl killing herself, he resigned a few days later. To close out the story, he talks about how he regrets the decisions he made when coding out the website, and he would change it if he could.

Its very important to remember you could potentially reach millions of people with your website, and if your advertising a product, it has to be truthful. Not just because of proper ethics, but it could cost the companys reputation. I think what he did was the right move, as I would not be able to work for a company knowing that I would be spreading a lie through my own work.

## Pythonisms

Q. What are dunder methods in Python, and how do they allow for the customization of built-in behavior in classes? Provide an example of a common dunder method and its purpose.

- python dunder methods are special methods that start and end with 2 under scores, such as...

      __init__ __str__ __len__

  dunder methods allow developers to emulate behavior and allows developers to tap into language features such as iteration, sequences, and attribute access. For example the dunder str method will return a readable string of an object. You can think of it as a print() function.

Q. Explain the concept of an iterator in Python. How do you create a custom iterator using the iter() and next() methods, and why are they important for enabling iteration in a class?

- A good way to think of iterators are like fancy loops. They are a way to iterate through an object and access its elements similar to a loop. Here is a simple implimentation...

      def class SimpleListIterator:
        def __init__(self, data):
          self.data = data
          self.index = 0

        def __iter__(self):
          return self

        def __next__(self):
          if self.index < len(self.data):
            value = self.data[self.index]
            self.index += 1
            return value
          else:
            raise StopIteration

  This takes in a list object and returns the values inside the list, such as list = [1, 2, 3, 4, 5]. Iterators are super important for classes because its how you can access the data values inside an object. Using the iter and next methods you can customize how values are accessed from your object.

Q. What is a generator in Python, and how does it differ from a regular function? Illustrate your answer with an example of a generator function using the ‘yield’ keyword.

- Generators are like syntactic sugar for iterators, you can cut down the amount of code quite a bit...

      def generator(value):
        while True:
          yield value

  What exactly is this doing and whats the difference? using a return statement to end your iteration would dispose of the local state, while using yield suspends the function, keeping the local state for later use. This is useful because you can continue iteration. Overall they are easier to read and use less code than standard iteration with iter and next dunder methods.

Q. Define decorators in Python and explain their primary use case. How can you create and apply a custom decorator to a function or method? Provide a simple example to demonstrate this concept.

- A decorator is prety much a funcion that wraps around another function to extend its functionality. They use the @ symbole. A good example of a decorator could be this greeting...

      def greeting(name):
        def hello():
          return "Hello, " + name + "!"
        return hello

      greet = greeting("Brenden")
      print(greet())  # prints "Hello, Brenden!"

  This example returns a function as a value. You put in a name for example, and it returns Hello, followed by the name/word you input.

## Bookmark and review

- [Decorators](https://realpython.com/primer-on-python-decorators/)

- [Dunder Methods](https://dbader.org/blog/python-dunder-methods)

- [Iterators](https://dbader.org/blog/python-iterators)

- [Generators](https://dbader.org/blog/python-generators)
