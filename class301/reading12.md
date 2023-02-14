# Class 12

[Back to home page](../README.md)

## Status codes in REST

Q. In your own words, describe what each group of status code represents:

- 100’s = Informational codes, usually stating the header part of the request is received.
- 200’s = These are success codes, mainly stating that a request was successful.
- 300’s = These are locational codes, usually letting the user know the information they requested is elsewhere.
- 400’s = These are client error codes, usually stating that something went wrong on the users side.
- 500’s = These are server error codes, usually stating that something went wrong on the servers side.

Q. What is a status code 202?

- 202 means a request was accepted and is often used for asynchronous processing.

Q. What is a status code 308?

- 308 means the user must use a different url to find the resource, or a permenant redirect.

Q. What code would you use if an update didn’t return data to a client?

- You could use the 204 (no content) code.

Q. What code would you use if a resource used to exist but no longer does?

- you could use a 410 (gone) code.

Q. What is the ‘Forbidden’ status code?

- 403 is a status code similar to 401 where the server understands the request but will not authorize because the user does not have the correct authorization to get the resource.

## Building a REST API quick

Q. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

- Because we dont this to deploy to localhost because localhost is local to our compter only.

Q. What is middleware?

- This is code that runs when a request is passed but before it gets passed to our routes.

Q. What does app.use(express.json()) do?

- This allows our server to accept a json file as a body rather than a element.

Q. What does the /:id mean in a route?

- this means the it is a parameter, this gives the user access to whatever they type in after the slash.

Q. What is the difference between PUT and PATCH?

- Patch is used for updating only the changed info rather than everything. This is useful if a user is updating a single or few parts of a piece of data.

Q. How do you make a default value in a schema?

- To make a default value, you define the value you want and use the .now method.

Q. What does a 500 error status code mean?

- 500 status means there is a error on the server side that stopped the request.

Q. What is the difference between a status 200 and a status 201?

- 200 means ok, pretty much stating nothing went wrong, while 201 means that the request was good and successfully created the resource.

## Things I want to know more about

When an API or service uses status codes over 599 (or custom codes) how do we identify what these mean when using their service? What is the best practice industry wise when it comes to custom codes and how do you make custom codes in your code to begin with?
