# Class 8

[Back to home page](../README.md)

## API design best practices

Q. What does REST stand for?

- Representational State Transfer.

Q. REST APIs are designed around a ____.

- Resource.

Q. What is an identifier of a resource? Give an example.

- The url is the identifier for a resource, and specifying what resource you want from the API.

Q. What are the most common HTTP verbs?

- GET, POST, PUT, PATCH, DELETE.

Q. What should the URIs be based on?

- The uri is suppost to represent the object that you are requesting.

Q. Give an example of a good URI.

- foo://example.com:8042/over/there?name=ferret found on [Google](https://www.google.com/search?q=good+uri+example&sxsrf=AJOqlzX9HlJ-la67k2HJE5yVaWkg6P1rJg%3A1675144042971&ei=aqvYY-v3Oom-0PEP8pOs4Ag&ved=0ahUKEwjr1IPtjfH8AhUJHzQIHfIJC4wQ4dUDCBA&uact=5&oq=good+uri+example&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIICCEQoAEQwwQ6BggAEAcQHjoICAAQBxAeEAo6DQgAEAcQHhAPEPEEEAo6CwgAEAgQBxAeEPEEOggIABAIEAcQHjoFCAAQogRKBAhBGABKBAhGGABQAFidBGDeBmgAcAF4AIABYIgBjgOSAQE1mAEAoAEBwAEB&sclient=gws-wiz-serp)

Q. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- A chatty api exposes a bunch of little requests inside the uri, so its important to limit them to make it easier for the client to get the resource they want. You can avoid this by combining similar resources into bigger resources.

Q. What status code does a successful GET request return?

- It should return status code 200(ok).

Q. What status code does an unsuccessful GET request return?

- It should return status code 404(not found).

Q. What status code does a successful POST request return?

- It should return status code 201(created).

Q. What status code does a successful DELETE request return?

- It should return status code 204(no content).

## Bookmark

-[RegExr](https://regexr.com/) - Pay particular attention to the cheatsheet

-[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

-[Regex 101](https://regex101.com/)

## Things I want to know more about

Are there any other identifiers for an API resource?
