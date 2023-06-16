# Class 28

[Back to home page](../README.md)

## Django forms

Q. How do Django Forms facilitate user input handling, and what are some key components of creating a form using the Django framework?

The basic process of a django form input handling consists of..

1. displaying the default page with form
2. receiving the user input data and showing any errors if necessary(redisplay form if needed)
3. perform the required actions based on the requested data and update/redirect the page

A key component of a django form is the form class, which simplifiys the entire form process.

Q. Explain the purpose of Django Templates in web development and describe how template inheritance can be utilized to improve code reusability and maintainability.

- Django templates provide dynamic content, meaning content can be generated based on data provided by the user. Template inheritance plays a big role in both code resability, as the templates can be reused for other purposes.

Q. Describe the function of Django Views in handling HTTP requests, and outline the differences between function-based views and class-based views.

- Function based views in django are much simpler than class based, as they are flexible all be it you have to provide more code. The main difference netween the 2 is class based views are object-oriented, and have built in functionality making it much easier to be reused and easily organised.

## Bookmark and review

- [Django Templates](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page)

- [Django Views](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views)
