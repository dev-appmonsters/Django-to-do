# Django-to-do
A dead simple Django ToDo Web App

This is a sample project that a novice django developer can use to get started.



## Features

- Dead simple
- Easily add, delete
- Simple UI
- Blazing fast

# Project Structure:

```
├── manage.py
├── Readme.md: documentation file
├── requirements.txt: requirements needs to be install
└── todo
    ├── static: contains design data to load
    ├── todo
    │   ├── settings.py: settings file for the project.
    │   ├── __init__.py
    │   ├── urls.py: url endpoints of linkedin scraper app
    │ 	└── wsgi.py	
    └── tasks
        ├── temaplates: contains templates to load
        ├── temaplatetags: contains templates tags to load data in templates 
        ├── __init__.py
        ├── migrations: database migrations
        ├── admin.py
        ├── app.py
        ├── models.py: database models for app
        ├── tests.py: test cases for view
        ├── urls.py: urls for app
        ├── forms.py: These forms are called by views
        └── views.py: These views are called by urls
```

## Setup

- Download the files from this repo
- Change the directory to the folder where you downloaded files
- For installing required packages, execute the following command in terminal:

    ```
    $pip install -r requirements.txt
    ```

- After successful installation execute the following commands:

    ```
    $python manage.py migrate
    $python manage.py runserver
    ```

- Visit `127.0.0.1:8000` in your browser to enjoy the awesome app!

Built with ♥ by [`Dev Appmonsters`]

