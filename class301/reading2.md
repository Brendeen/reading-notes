# Class 2

[Back to home page](../README.md)

## React lifecycle

Q. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

- Render will come first.

Q. What is the very first thing to happen in the lifecycle of React?

- mounting is the first state to happen in the lifecycle, this state happens when a component is being created and inserted into the DOM.

Q. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

- constructor, render, react updates, componentDidMount, componentWillUnmount.

Q. What does componentDidMount do?

- componentDidMount is used to execute react code when the component is in the DOM.

## React state vs props

Q. What types of things can you pass in the props?

- the parent passes the child component information that can be HTML attributes, but can also pass through JS attributes like arrays, objects and functions.

Q. What is the big difference between props and state?

- props are used like arguments in a function, they are the initial things you want to pass through your component to render. While states are used inside the component rather than outside, updating it through the component.

Q. When do we re-render our application?

- When you change the state it updates automatically, while with a prop you have to manuelly update it for the component to rerender.

Q. What are some examples of things that we could store in state?

- State is primarilly used for updating a component after a user has put in some input. Some examples could include changing a background color, pausing and unpausing a video, or a form. Any form of user input to update the page.

## Things I want to know more about

I want to look more into the semantics of state and props and how they differ from eachother.
