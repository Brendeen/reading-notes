# Class 34

[Back to home page](../README.md)

## API Deployment

Q. What are the key principles to follow when organizing and configuring Django settings for a project, according to the “Django Settings Best Practices” reading?

1. Keep settings in environment variables
2. Write default values for production configuration (excluding secret keys and tokens)
3. Dont hardcode sensitive settings, and dont put them in VCS
4. Split settings into groups: Django, third-party, project
5. Follow naming conventions for custom (project) settings

  Referenced from [djangostars](https://djangostars.com/blog/configuring-django-settings-best-practices/)

Q. How does the White Noise library contribute to the efficient serving of static files in a Django application, and what are the steps to integrate it into a project?

- Whitenoise improves performance by serving static files in the app, using caching techniques during the production of your application. The stepsto integrate whitenoise are
  1. pip install whitenoise
  2. add whitenoise to your MIDDLEWARE inside settings.py

          MIDDLEWARE = [
              # ...
              "django.middleware.security.SecurityMiddleware",
              "whitenoise.middleware.WhiteNoiseMiddleware",
              # ...
          ]

  3. Configure caching by adding...

          STATICFILES_STORAGE = 'whitenoise.storage.CompressedManifestStaticFilesStorage'

       under STATIC_URL = '/static/' inside your settings.py.

Q. What is the purpose of Cross-Origin Resource Sharing (CORS) in web applications, and how can it be implemented and configured in a Django project to control access to resources?

- CORS is a mechanism that allows web browsers to make requests to different domains than the one from the initial web page. Its pretty much a security system to mitigate risks with cross-origin requests. You can Impliment it by
  1. pip install django-cors-headers
  2. add 'corsheaders', to your INSTALLED_APPS and 'corsheaders.middleware.CorsMiddleware', to your MIDDLEWARE inside settings.py
  3. specify CORS Settings inside settings.py

          CORS_ALLOWED_ORIGINS = [
          # List of allowed origins (domains) for cross-origin requests
          # e.g., 'https://example.com'
          ]

          CORS_ALLOW_METHODS = [
              'GET', 'POST', 'PUT', 'PATCH', 'DELETE', 'OPTIONS'
              # List of allowed HTTP methods for cross-origin requests
          ]
  4. Fine tune settings to your needs.

## Bookmark and review

- [White Noise](http://whitenoise.evans.io/en/stable/)

- [CORS](https://en.m.wikipedia.org/wiki/Cross-origin_resource_sharing)
