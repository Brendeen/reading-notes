# Class 39

[Back to home page](../README.md)

## React 3

Q. What is React Context, and how does it help in managing state and data sharing in a React application?

- Context in react is a way to pass data to components without the use of props, allowing your components to share state way more easily. It was made for features that dont need to be updated to often such as user theme settings, and because of this, its not a replacement for statemanagment. React context removes the process of prop drilling (meaning the process of passing props through components that dont need it) by using the createContext method to wrap your component and give it a value

Q. Explain the useContext Hook and how it can be used to access data from a React Context within a functional component.

- To start off you will want to import the hook...

      import { useContext } from 'react'

  so we can use it. This hook allows functional components to consume data from a React context. This is expecially useful when multiple components need access to specific data, we can use useContext to avoid passing props manuelly.

  Super helpful video on [useContext](https://www.youtube.com/watch?v=5LrDIWkK_Bc)

Q. Describe the purpose of Next.js, and provide an example from the Vercel Next.js Examples reading on how it can be used to build a scalable web application.

- Some of the main reasons why you would want to use Next js is because of its features such as server-side rendering, static site generation and code splitting. A great example is a blog because you can staticly render using static generation, using markdown to initialise the post, and use remark and remark-html to convert the MD files to hrml and send it down as props. [Example blog link](https://github.com/vercel/next.js/tree/canary/examples/blog-starter)

## Bookmark and review

- [Next.js Examples](https://github.com/vercel/next.js/tree/canary/examples)

- [Why I’m using Next.js in 2020](https://www.youtube.com/watch?v=rtgbaKBhdkk)

- [React Contect for Beginners](https://www.freecodecamp.org/news/react-context-for-beginners/)
