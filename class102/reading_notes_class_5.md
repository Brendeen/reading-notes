# Class 5

[Back to home page](../README.md)

In this class, we looked at **CSS**, or *Cascading Style Sheets*.

If html is the structure, or the skeleton of a website, than html is the styling or clothing, accesories, and hair of a website. Css is what makes a website look unique from everything else on the web.

## What is Css?

Css takes elements from html and puts them into groups of elements to style with specific commands. For example you could turn all of your text (p) into a specific color or make a heading (h1) bigger or smaller. 

Css typically starts with the element you want to be modified, and then using a curly bracket {} to start and end the command. You then need to specify what you want changed.

h1 {

    color: green
    font size: 12em

}

This is an example of changing both the size and color of an h1 heading. This specific command would turn the text green and make the heading 12 emphemeral units, or equivilant to the size in inchs.

These commands change the **properties** of an element and apply the desired styling.

Here is a [CSS Style Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) reference sheet.

The css language is broken down into different modules that contain different commands. Any sort of color changing commands would be sorted together like the **background-color** and **boarder-color** commands.

There are 3 types of css,

- **External CSS**
- **Internal CSS**
- **Inline CSS**

External css can change a file from a whole other .css file. internal css can change a single html file, but only if it has a unique style. These commands are incorperated right into the html file. Lastly inline css can change any single element with a unique style, and can contain any css property.

**To include a link to an external css file**, use the command-

< link rel="stylesheet" href="mystyle.css" >

### Colors

Colors are a completely different topic and can be complicated in their own way. Ill just list a few for examples-

- Hexadecimal colors
- Hexadecimal colors with transparancy
- RGBA colors
- RGBA colors
- HSL colors
- HSLA colors

Heres a link explaining all the different [Colors](https://www.w3schools.com/cssref/css_colors_legal.asp) and how they work.