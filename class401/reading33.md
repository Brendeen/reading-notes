# Class 33

[Back to home page](../README.md)

## Authentication and production

Q. What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?

- The purpose of a JWT is a secure way to transmit information in the form of a JSON object. The object is seperated into 3 parts...

  - Header
  - Payload
  - Signature

  These 3 parts all have a specific task in encoding and decoding data. The header contains the type and signing algorithm.

      {
        "alg": "HS256",
        "typ": "JWT"
      }

  The Payload are the claims, such as registered, public, and private claims.
  
      {
        "sub": "1234567890",
        "name": "John Doe",
        "admin": true
      } 

  Lastly the signature pretty much what it sounds like, a signature. You take the header and the algorithm specified, the encoded data, and sign it.

      HMACSHA256(
        base64UrlEncode(header) + "." +
        base64UrlEncode(payload),
        secret)

  Referenced from [jwt.io](https://jwt.io/introduction/)

Q. How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?

- Firstly and most importantly you need to have a DRF project, followed by basic setup and instalation. Next access your token to view your data, this is obtained at the endpoint /api/token/.

      http post http://127.0.0.1:8000/api/token/ username=vitor password=123

  Example code.

  This access token is stored in local storage and expires after about 5 minutes. The next important bit is the refresh token, which can be accessed at the endpoint /api/token/refresh/.

      http post http://127.0.0.1:8000/api/token/refresh/ refresh=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b2tlbl90eXBlIjoicmVmcmVzaCIsImV4cCI6MTU0NTMwODIyMiwianRpIjoiNzAyOGFlNjc0ZTdjNDZlMDlmMzUwYjg3MjU1NGUxODQiLCJ1c2VyX2lkIjoxfQ.Md8AO3dDrQBvWYWeZsd_A1J39z6b6HEwWIUZ7ilOiPE

  Example code.

  This will expire after 24 hours and the user will have to perform the actions again to get a another set of tokens.

  Steps followed from [simpleisbetterthancomplex.com](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)

Q. Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?

- Djangos runserver was not built with speed or security in mind, it was solely made for the developer to view their webpage locally for quick access. A great alternative is Gunicorn and Nginx, which is a great production stack.

  "If you want to run Django in production, be sure to use a production-ready web server like Nginx, and let your app be handled by a WSGI application server like Gunicorn."

  Sourced from [vsupalov.com](https://vsupalov.com/django-runserver-in-production/)

## Bookmark and review

- [Ginicorn](https://gunicorn.org/)

- [Django Migrations Primer](https://realpython.com/django-migrations-a-primer/)
