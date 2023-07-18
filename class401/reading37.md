# Class 37

[Back to home page](../README.md)

## React 1

Q. In the context of ES6 Syntax and Feature Overview, what are three key features introduced in ES6 that improve upon the previous version of JavaScript, and briefly explain their benefits?

- Overall ES6 adds alot of quality of life changes to JS. Mainly small changes like making declarations simpler. As well as adding let and const variable declaration. Most of these quality of life changes do things such as changing multi line declarations to single lines, or re assigning variables easier.

Q. After reading “Tailwind in 15 minutes,” can you describe the purpose of utility classes in Tailwind CSS and provide an example of how to use them to style an HTML element?

- Tailwind utility classes have some of the following benefits...

  1. Easy to read
  2. viewability, using onlt the html file instead of a css file
  3. using constraints, you can follow a design, following a uniform design
  4. media queries, meaning you can add functionality to support smaller devices like smart phones and tablets after the designs are made
  5. endless possibilities, you can create unique componetns using these designs

  styling an html attribute starts with npm install tailwind and configure the content array to watch over all html and js files. After creating an html and css file inside a src folder, put the proper dependancys inside the css file

      @tailwind base;
      @tailwind components;
      @tailwind utilities;

  here is an example of what an h2 element could look like with tailwind:

      <h2 class="text-lg text-red-500 border-b border-black-600 mb-3">
        Hello
      </h2>

Q. Based on “Why to use Next.js,” explain the main advantages of using Next.js for web development, and provide a brief comparison between traditional client-side rendering and Next.js’s server-side rendering approach.

- Next.js offers some great features that put it above its competetors, such as built-in routing, server-side rendering, and automatic code splitting. Some of the comparisons for server-side and client-side rendering include...

  1. scalability
  2. performance
  3. code splitting
  4. dev experience

  overall Next.js is a free service to upgrade your website performance using server-side rendering, automatic code splitting and an overall better/easier experience for developers.
