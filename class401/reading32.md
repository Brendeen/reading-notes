# Class 32

[Back to home page](../README.md)

## Permissions & Postgresql

Q. What are the key components and purpose of Django Rest Framework (DRF) permissions, and how do they help in securing an API?

- You can set a permission policy inside the settings of the project under the REST_FRAMEWORK section, the default will look like this ...

      REST_FRAMEWORK = {
        'DEFAULT_PERMISSION_CLASSES': [
            'rest_framework.permissions.AllowAny',
        ]
      }
  This setting allows any user to access the information. You can also alter the policy using the APIView class-based views. Using permissions makes it easy to block data from certain users that either dont need to see it or dont have the permissions to.

Q. In SQL, what is the purpose of the SELECT statement, and how would you use it to retrieve all columns from a table called ‘employees’?

- The select statement allows you to access data from a database. In this case, to retreive all the data on employees, you could use the line...

      SELECT * FROM employees;

  The * star accesses all rows in the table.

Q. Can you explain the role of DRF Generic Views and provide examples of their usage in building a RESTful API?

- DR Generic views are a powerful tool for django rest apis that provide default premade views to cut down on coding and make crud operations much easier.

## Bookmark and review

- [Classy Django REST](http://www.cdrf.co/)

- [DRF Generic Views](https://www.django-rest-framework.org/api-guide/generic-views/)
