# Class 10

[Back to home page](../README.md)

## Trobleshooting JS

Q. Name some key differences between a Syntax Error and a Logic Error.

- A syntax error happens when you are missing or incorrectly spelled a line or tag wrong, and a logic error is when the code runs, but produces he wrong kind of output, such as incorrect data.

Q. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

- Ive had many syntax errors, but one of the more frusterating ones was when I kept getting an error because my constructor was written improperly, I thought I had to run a constructor off of an existing object, but I was very very wrong. I rewrote the code a bit and deleted the object.
- I had a logic error in lab 4 where I made a for loop that was suppost to break when the right number was guessed, but instead it would continue to loop if there were still guess attempts. I figured out I needed to use the break tag after a correct guess was made in my if statement.
- Another logic error I had in lab 7 was presenting my data on a whole other table. Turns out I had made the data in a seperate table and thats what was making it appear outside the table, so I deleted the table tag and moved it into the function for my rendering.

Q. How will this topic continue to influence your long term goals?

- Errors are always going to pop up, nobody is perfect, so Ill have to take them as learning opportunites everytime a new error shows up in my console.

## The JavaScript Debugger

Q. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

- The debugger is a useful tool in the browser that gives you a live feed of your page. You can make changes and see how it would impact your website, as well as view the console for errors. This is very useful for debugging as the console will show you the exact line of code the error shows up on, making debugging for syntax errors much more managable.

Q. Define what a breakpoint is.

- breakpoints are points you can set in the debugger to pause execution of js elements and identify where problems are.

Q. What is the call stack?

- The call stack is a mechanism that keeps track of all active functions in your script. It keeps track of what functions are being run and what those functions execute.

## Things I want to know more about

Debugging is something we've been using very casually for awhile now and breakpoints are something I personally have never used. Getting to know and use this feature of the debugger seems like a great skill to know.
