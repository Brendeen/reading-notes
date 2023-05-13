# Class 17

[Back to home page](../README.md)


## Web scraping

Q. What are the key differences between scraping static and dynamic websites?

- The main difference is static sites are prerendered, while a dynamic page generates a response for the user in real time on page load.

Q. Explain at least three techniques or best practices that can be employed to avoid getting blocked while scraping websites.

- Make sure your bot doesnt slam the server when accessing the data as this could cause the website to overload, avoid similar crawling patterns, and avoid obvious "honey pot" traps.

Q. What is Playwright, and how does it assist in web scraping tasks? Provide an example of a use case where Playwright would be particularly beneficial.

- Playwright is a library that can automate various browsers and assist with data scraping from websites using these browsers, alongside other imports like BeautifulSoup, a practical use of data scraping would be loging into a website and parsing a certain element set like all the h2s in a document to find the specific html data you want.

Q. Describe the purpose of using Xpath in web scraping, and provide an example of an Xpath expression to select a specific HTML element from a webpage.

- Xpath is great for finding html elements by their tag, attribute or position in an html webpage. For example if you wanted to find the title for a page you could write -

//h1[1]

## Bookmark and review

- [Xpath Cheatcheet](https://devhints.io/xpath)

## Things I want to know more about

When scraping from websites, what is the best industry practice? How can you get unblocked from data scraping if you are caught/unwanted?
