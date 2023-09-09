# blogging-website
## Blogging Web App with Django

Welcome to the Blogging Web App built with Django! This is a powerful platform for creating, managing, and sharing your blog posts. Whether you're a blogger, writer, or content enthusiast, this app provides you with the tools to publish and engage with your audience.
## Table of Contents
                                                                                    blogging-website
                                                                                           |
                                                              ----------------------------------------------------------------------------------------------
                                                              |               |                              |                             |               |
                                                              manage.py      blog                           blogging                     templates       dbsqlite3
                                                                               |-->urls.py                     |-->views.py                 |-->base.html
                                                                               |-->wsgi.py                     |-->model.py                 |-->index.html
                                                                               |-->asgi.py                     |-->urls.py                  |-->dview.html
                                                                               |-->__init__                    |-->test.py
                                                                               |-->pycache__                   |-->apps.py
                                                                                  |-->urls.cpython-311         |-->admin.py
                                                                                  |-->wsgi.cpython-311         |-->__init__.py
                                                                                  |-->__init__.cpython-311     |-->pcache__
                                                                                  |-->settings.cpython-311     |-->migrations
                                                                                                                   |-->__init__.py
                                                                                                                   |-->0001_initial.py
                                                                                                               


## Getting Started


### Prerequisites

Before you get started, make sure you have the following software installed:
-->Python version 3.11.5(https://www.python.org/)
-->Pip version 23.2.1
-->Django (if not installed than install it through command prompt by typing "pip install django")
-->Pycharm or any other IDE( if want to install pycharm  than use the link "https://www.jetbrains.com/pycharm/")
-->SQlite
-->Git


####Create and apply database migrations:
"python manage.py makemigrations
python manage.py migrate"
####Create a superuser for admin access:
"python manage.py createsuperuser"
####Start the development server:
"python manage.py runserver"

Open your web browser and navigate to http://localhost:8000/admin to access the admin panel. Use the superuser credentials you created to log in

  ## Features

- **Authenticated admin panel:** Secure registration and login functionality.
- **Create and Edit Posts:** Easily write, edit, and format blog posts using Django's admin panel.
- **Search Functionality:** Quickly find and navigate to the content you're looking for.
- **Filtration  Functionality:** Quickly find and navigate to the content in the admin panel.
- **Responsive Design:** Ensures a seamless experience across various devices and screen sizes.

### Usage
1.Log in to the admin panel to manage posts, categories, tags, and user accounts.
2.Create a new blog post, specifying the title, content, category, and tags.
3.Click "Publish" to make your post live.
4.Explore other posts on the platform by using the search and category features.
