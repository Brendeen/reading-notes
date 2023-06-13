# Class 27

[Back to home page](../README.md)

## Django models

Q. Explain the purpose and basic structure of Django models. How do they help in creating and managing database schema in a Django application?

- Models define the structure of data stored in the database. Whats great about models is after you pick your database (MySQL, MariaDB, Oracle, etc...) you dont need to talk to the database. The model structure will communicate with the database, meaning Django will handle all the heavy lifting. Simply put, django models are how you can access data from your database through python objects.

Q. Describe the primary features and functionality of the Django Admin interface. How can it be customized to suit the specific needs of a project?

- The Django Admin interface is a powerful built-in feature that provides a user-friendly and customizable interface for managing the administrative tasks of a Django project. It offers several primary features and functionalities such as CRUD operations, automatic interface generations, and user authentication/permissions.

Q. Briefly outline the key components and workflow of a Django application, as discussed in the Beginner’s Guide to Django. How do these components interact with each other to create a functional web application?

- The main pieces of a django application are the project itself, and the apps located inside. These function together with a databse to make WRR (web request responses). Django uses MTV, or Model Template View functionality. Each piece has a certain part in the application, with the project almost acting as the supervisor and running the apps inside the web application.

## Bookmark and review

- [Beginner's Guide to Django - Part 2](https://simpleisbetterthancomplex.com/series/2017/09/11/a-complete-beginners-guide-to-django-part-2.html)
