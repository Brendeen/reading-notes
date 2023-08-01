# Class 41

[Back to home page](../README.md)

## React 4

Q. Explain the concept of dynamic routes in Next.js and how they differ from static routes.

- The main difference between static and dynamic routes is that on a request, a dynamic route is created, while on build time a static route is created. A dynamic route is either prerendered or filled on a request time

Q. Describe the process of deploying a Next.js application. What are the key steps involved, and what are some deployment platforms you can use?

- First and most importantly you want to build out your application and connect any other code bases you have such as a backend. Then select your provider. (We will be using Vercel) configure your settings to your liking and deploy.

Q. How does Next.js handle static file serving? Discuss the default folder structure for storing static assets and explain how to reference them in a Next.js application.

- Next.js follows a specific way to handle static files by placing them inside a folder called public where they can be accessed by using the following syntax...

      /file-name.filepath

  This file structure makes referencing these files easy and simple.

## Bookmark and review

- [Next.js - Static File Serving](https://nextjs.org/docs/basic-features/static-file-serving)

- [Next.js 10 is here](https://www.youtube.com/watch?v=JWCS5IdECVI)
