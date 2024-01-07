# learning_Django
this repo is for learning Django basics
## basic Django commands
to create a new project using Django type `django-admin startproject <project_name>` inside a terminal.   
to create a new app `cd` into your `<project_folder` and type `python manage.py startapp <app_name>`

### creating App
once you create an app, go to the [project_name/project_name/settings.py](MyStore/MyStore/settings.py) and add the `app_name` to the `INSTALLED_APPS` list.

### creating a view
to create a view go to [your_app/views.py](MyStore/core/views.py) file and create a new function. the function takes in `request` as argument and returns an render with the request. it also takes path to where the `html` file is located.

Then go to [project_name/project_name/urls.py](MyStore/MyStore/urls.py) and add the current url to the `urlpatterns`. this will let us reach the `html page`