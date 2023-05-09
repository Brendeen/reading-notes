# Class 16

[Back to home page](../README.md)

## Serverless computing

Q. What are the key characteristics of serverless computing, and how does it differ from traditional server-based architectures?

- In serverless computinh, the main benefit is a seperate party handles the back end functionality, so the developers can focus on making the best front end they can. Though the name is miss leading, there is a backend handled by the provider. The provider charges the client when an event is fired off (such as making a request to receive resources from a database).

Q. How can one get started with Vercel, and what are the main steps involved in deploying a serverless function using Vercel?

- To start, you want to connect your github and import your desired project. From there, you code your application, preview before pushing, and finally ship (in this case to main where it is deployed). From there Vercel will ship your changes to production for everyone to see.

Q. What are APIs, and how can they be utilized in Python applications to access and manipulate data from external sources?

- You can think of APIs as a form of communication. They allow different pieces of code to communicate and understand eachother. An Application Programming Interface sends http requests to the server, and retreives the users desired data.

Q. What is the Requests library in Python, and how can it be used to interact with APIs by sending HTTP requests? Can you provide an example of a basic GET request using the Requests library?

- The python request api allows the user to make http requests very easily. A common example of an http request is updating data, or PUT. Some other examples could be retreive(GET), create(POST), or delete(DELETE).

## Bookmark and review

- [Serverless Functions](https://vercel.com/docs/concepts/functions/serverless-functions)

- [Effective python enviroment](https://realpython.com/effective-python-environment/)

## Things I want to know more about

From a big company such as Google or Facebook, how common is it for them to use a serverless application? Is it more common for smaller companys? What is the most reliable serverless provider?
