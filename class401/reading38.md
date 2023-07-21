# Class 38

[Back to home page](../README.md)

## React 2

Q. How does lifting state up in a React application help with managing data flow and what are the benefits of using this approach?

- The process of lifting state is pretty much moving state (data) of multiple components into a parent component in the component tree. This way the state for that component or multiple components becomes a single source so every component that needs to access that state. Some of the benefits include single source of truth which simplifies data flow, easier manipulation of state, and much better reusability sense every components can have access to the data.

Q. Explain the concept of conditional rendering in React and provide an example of how to implement it in a component.

- Conditionally rendering will allow you to which piece of ui is displayed at a time based on the conditions. This is great for user interfaces because it will change depending on the users interaction, making it a powerful dynamic user interface. A common way to impliment this is through an if-else statement, but you can also && operator or the ternary ? : operator. For example if the user is logged in, you could render a component to show the users name or other information they have filled out, maybe even a theme/setting like dark or light mode.

Q. What are the main principles behind “Thinking in React” and how do they guide the process of designing and building a React application?

- When thinking in react, you have to break down your application into a few pieces, Firstly, what will the componets look like/do. Second, describe what each components state will do. Finally, connect the components and data so data can flow through each component seemlessly. Having things like a mockup for reference is also very useful because you can get a visual as to what the app will look like, making it easier to seperate the different components. A proper way to design a react app goes like this...

  1. Start with mockup and break down ui into a component hierarchy
  2. Build static app in react
  3. acheive MVP of UI state
  4. identify where the state should live
  5. Add inverse data flow

## Bookmark and review

- [React - Comprehensive Guide](https://tylermcginnis.com/reactjs-tutorial-a-comprehensive-guide-to-building-apps-with-react/)

- [Heroicons](https://heroicons.com/)
