# [Adminator Django](https://appseed.us/product/adminator/django/)

Open-source **Django Dashboard** generated by `AppSeed` op top of an iconic design. For newcomers, **[Adminator](https://appseed.us/product/adminator/django/)** is one of the best open-source admin dashboard & control panel theme. Built on top of Bootstrap, `Adminator` provides a range of responsive, reusable, and commonly used components. 

- 👉 [Adminator Django](https://appseed.us/product/adminator/django/) - product page
- 👉 [Complete documentation](https://docs.appseed.us/products/django-dashboards/adminator) - `Learn how to use and update the product`
- 🚀 Free [support](https://appseed.us/support/) for **registered users** (Email & `Discord`) 

<br />

> Built with [App Generator](https://appseed.us/generator/), timestamp `2022-12-01 14:50`

- `Up-to-date dependencies`
- Database: `sqlite`
- UI-Ready app, Django Native ORM
- `Session-Based authentication`, Forms validation

<br />

![Adminator Dashboard - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/173175611-63faf177-33d8-4238-ad0b-271a16465bd0.png)

<br />




## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/2736fc92-1fc5-4609-a3c5-29ec42912327.git
$ cd 2736fc92-1fc5-4609-a3c5-29ec42912327
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

### 👉 Create Users

By default, the app redirects guest users to authenticate. In order to access the private pages, follow this set up: 

- Start the app via `python manage.py runserver`
- Access the `registration` page and create a new user:
  - `http://127.0.0.1:8000/register/`
- Access the `sign in` page and authenticate
  - `http://127.0.0.1:8000/login/`

<br />

## ✨ Code-base structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- core/                               # Implements app configuration
   |    |-- settings.py                    # Defines Global Settings
   |    |-- wsgi.py                        # Start the app in production
   |    |-- urls.py                        # Define URLs served by all apps/nodes
   |
   |-- apps/
   |    |
   |    |-- home/                          # A simple app that serve HTML files
   |    |    |-- views.py                  # Serve HTML pages for authenticated users
   |    |    |-- urls.py                   # Define some super simple routes  
   |    |
   |    |-- authentication/                # Handles auth routes (login and register)
   |    |    |-- urls.py                   # Define authentication routes  
   |    |    |-- views.py                  # Handles login and registration  
   |    |    |-- forms.py                  # Define auth forms (login and register) 
   |    |
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/                     # Templates used to render pages
   |         |-- includes/                 # HTML chunks and components
   |         |    |-- navigation.html      # Top menu component
   |         |    |-- sidebar.html         # Sidebar component
   |         |    |-- footer.html          # App Footer
   |         |    |-- scripts.html         # Scripts common to all pages
   |         |
   |         |-- layouts/                   # Master pages
   |         |    |-- base-fullscreen.html  # Used by Authentication pages
   |         |    |-- base.html             # Used by common pages
   |         |
   |         |-- accounts/                  # Authentication pages
   |         |    |-- login.html            # Login page
   |         |    |-- register.html         # Register page
   |         |
   |         |-- home/                      # UI Kit Pages
   |              |-- index.html            # Index page
   |              |-- 404-page.html         # 404 page
   |              |-- *.html                # All other pages
   |
   |-- requirements.txt                     # Development modules - SQLite storage
   |
   |-- .env                                 # Inject Configuration via Environment
   |-- manage.py                            # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />



## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Soft UI Dashboard is a premium Bootstrap 5 Design now available for download in Django. Made of hundred of elements, designed blocks, and fully coded pages, Soft UI Dashboard PRO is ready to help you create stunning websites and web apps.

- 👉 [Soft UI Dashboard PRO Django](https://appseed.us/product/soft-ui-dashboard-pro/django/) - Product Page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![Soft UI Dashboard PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/170829870-8acde5af-849a-4878-b833-3be7e67cff2d.png)

<br />

---
[Adminator Django](https://appseed.us/product/adminator/django/) - Open-source starter generated by **[App Generator](https://appseed.us/generator/)**.
