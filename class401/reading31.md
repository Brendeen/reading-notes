# Class 31

[Back to home page](../README.md)

## Django REST framework and Docker

Q. What are the key components of a Docker container, and how do they help streamline the development and deployment of applications?

- The docker is a way to run linux containers, which are alternative to virtual machines. The keycomponents for the docker include...
  1. Docker Engine.
  2. Docker Containers
  3. Docker images
  4. Docker Client
  5. Docker daemon

Q. Describe the primary steps involved in building a library website using Django, including essential components like models, views, and templates.

- First and foremost you have to create a django project, and create an app for the library. Inside the model for your app, you will want to include all the basic information needed for a library book, like author, title, isbn etc and of course make your migrations with the commands...

      python manage.py makemigrations
      python manage.py migrate

  Register our model in the admin file, and create a superuser so we can log into our database. The last steps follow our VUT, meaning create view classes, url patterns, and lastly a base.html template and coresponding html files to display the books we create in out templates file. Provide tests as needed.

Q. Can you explain the primary differences between Django and Django REST framework?

- Django is mainly used to make web applications, while django frameworks is used to build restful apis and has extra tools to delelop them.

  "The most important takeaway is that Django creates websites containing webpages, while Django REST Framework creates web APIs which are a collection of URL endpoints containing available HTTP verbs that return JSON."

  Quoted from [djangoforapis.com](https://djangoforapis.com/library-website-and-api/)

## Bookmark and review

- [Beginner's Guide to Django REST Framework](https://learndjango.com/tutorials/official-django-rest-framework-tutorial-beginners)
