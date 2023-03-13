# [Soft Dashboard Tailwind Django](https://appseed.us/product/soft-dashboard-tailwind/django/)

Open-source **Django Dashboard** generated by `AppSeed` op top of a modern design. Designed for those who like bold elements and beautiful websites, **[Soft UI Dashboard](https://appseed.us/product/soft-dashboard-tailwind/django/)** is ready to help you create stunning websites and webapps. **Soft UI Dashboard** is built with over 70 frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining - Designed by [Creative-Tim](https://www.creative-tim.com/?AFFILIATE=128200) 

- 👉 [Soft Dashboard Tailwind Django](https://appseed.us/product/soft-dashboard-tailwind/django/) - `product page`
- 👉 [Soft Dashboard Tailwind Django](https://django-soft-dashboard-tailwind.appseed-srv1.com/) - `LIVE Demo`

<br />

> Features

- ✅ Design: [Soft Dashboard](https://www.creative-tim.com/product/soft-ui-dashboard-tailwind?AFFILIATE=128200) by `Creative-Tim`
- ✅ Styling: `Tailwind CSS`
- ✅ `Up-to-date dependencies`
- ✅ `Session-Based authentication`, Forms validation
- ✅ `Admin Section` Styled (reserved for superusers)
- ✅ `Docker`
- 🚀 `CI/CD` flow via `Render`
  - See `video presentation`: **[Django and Tailwind, deploy LIVE](https://www.youtube.com/watch?v=2cwuqAlFfnw)**
  
<br />

![Soft UI Dashboard - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/168843143-f2a2ffac-4ab6-44d2-bc1f-a9a8682a749b.png)

<br /> 

## Start with `Docker`

> **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ git clone https://github.com/app-generator/django-soft-dashboard-tailwind.git
$ cd django-soft-dashboard-tailwind
```

<br /> 

> **Step 2** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />

## Manual Build

> Download the code 

```bash
$ git clone https://github.com/app-generator/django-soft-dashboard-tailwind.git
$ cd django-soft-dashboard-tailwind
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

> Create Superuser

```bash
$ python manage.py createsuperuser
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

## Create Users

By default, the app redirects guest users to authenticate. In order to access the private pages, follow this set up: 

- Start the app via `flask run`
- Access the `registration` page and create a new user:
  - `http://127.0.0.1:8000/register/`
- Access the `sign in` page and authenticate
  - `http://127.0.0.1:8000/login/`

<br />

## Codebase Structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- core/                            
   |    |-- settings.py                   # Project Configuration  
   |    |-- urls.py                       # Project Routing
   |
   |-- home/
   |    |-- views.py         # APP Views 
   |    |-- urls.py          # APP Routing
   |    |-- models.py        # APP Models 
   |    |-- tests.py         # Tests  
   |  
   |-- templates/
   |    |-- includes/        # HTML chunks and components   
   |
   |-- static/
   |    |-- CSS, JS, Images  # CSS files, Javascripts files   
   |
   |-- requirements.txt      # Project Dependencies
   |
   |-- env.sample            # ENV Configuration (default values)
   |-- manage.py             # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />

## Customize CSS

- Edit the `static/assets/scss/styles.css`
- Regenerate the CSS using `NPM` or `Yarn`

```bash
$ npm i            # Install modules
$ npm run build    # Recompile SCSS to CSS
$ npm run min-css  # Minify CSS
$ // OR 
$ yarn             # (via Yarn) Install modules
$ yarn build       # (via Yarn) Recompile SCSS to CSS
$ yarn min-css     # (via Yarn) Minify CSS
```

<br />

---
[Soft Dashboard Tailwind Django](https://appseed.us/product/soft-dashboard-tailwind/django/) - Free starter provided by **[AppSeed](https://appseed.us/)**.
