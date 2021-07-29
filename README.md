## Storm E-Commerce Store

- This is a fullstack e-commerce store using python and django rest framework using Vue for the frontend. Users are able to scroll through the store based on 2 season, as well as searching for products individually. Users can browse and add items to the cart without signing in or signing up. Users can also signup and sign in to actually purchase the items in their cart.

- The admins of the site can log in via the superuser as well as perform full crud for other admins for their staff. The admin can address orders that have been placed as well as upadate all info for clients as well as products in the store.

## Dependencies

- django
- django-rest-framework
- djoser
- pillow
- django-cors-headers
- stripe
- axios
- bulma
- core-js
- vue
- vue-router
- vuex

# Requirements

- Python 3 or higher
- Pipenv
- npm
-

## Set Up Guide

First thing is clone the repository:

    $ git clone https://github.com/aanand93/django-ecom-store.git
    $ cd django-ecom-store

Then Create a virtual environment:

    $ cd storm_django
    $ pipenv shell

Then install all dependencies for the backend:

    $ pipenv sync

Then run the server:

    $ python manage.py runserver

Go to http://127.0.0.1:8000/api/v1/admin in your browser to log into the admin profile.

Now we must set up the frontend by opening a new terminal in vscode or in your regular terminal:

    $ cd django-ecom-store
    $ cd storm-vue
    $ npm i
    $ npm run serve

Go to http://localhost:8080/ to view the app in your browser.
