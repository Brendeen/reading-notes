# Class 6

[Back to home page](../README.md)

In this class we looked into **Javascript**.

## What is Javascript?

There are 3 distinct parts of java script-

1. The language itself
2. The DOM API, this is what interacts with the web page.
3. The server API which is provided by one of the various server-side systems.

There are **two** ways to embed javascript into a web page. You can either connect it from a seperate file in the text editor similarly to how you connect a seperate css file, or embed it straight into the html file with the tag < script >< /script >.

One of the more simple commands for javascript is the alert command, this will pop up an alert on the users screen when entering the web page.

**< script language="javascript">**

**alert("Hello World");**

**</ script>**

Another example are commands around **prompt** and **confirm**. With these commands you can make a pop up similar to alert but with interactive gimicks.

< script>

var name = prompt("Your name:", "");

document.write("Hello ", name);

< /script>

In this prompt example, the user types their name in the box and presses ok. The website should update with the phraze "Hello (whatever name you typed)" in the corner of the page

< script>

if (confirm("Shall I print Hello World?")) {
    document.write("Hello World");
} else {
    document.write("OK, I won't print it.");
}

< /script>

In this confirm example, the user will be faced with a ok or cancel question. depending on what they choose the site will update in that specific way. If the user hits ok, the site will update with "Hello World". And if the user hits cancel, "the site will update with the phrase " OK, I won't print it.".

### Variables

Variables are containers for storing data, there are 4 ways to declare them:

- vae
- let
- const
- Typing nothing

var is an older variable declaration that can be used for older browsers, though most developers **const** today. However, if a variable can change, you use the **let** declaration. Here is an example-

const price1 = 5;
const price2 = 6;
let total = price1 + price2;

All variables in javascript should have an identifier, or a name for the variable. They can be as simple as "x" and "y", or as complicated as you like. Identifiers are case-sensative as well, so "x" and "X" are seperate variables. Here is a breakdown of
[JavaScript-variable-rules](https://www.w3schools.com/js/js_variables.asp).

#### Debugging

Debugging, or *finding and fixing errors* in your code, is a very important part of javascript. Most browsers will have a hidden window called a JavaScript console where the browser can write warnings/errors that have been executed by javascript. Developers can also write debug information in the console by using the command console.log(). To open the console on Chrome use the following button prompt: **Command-Option-J**