# djangotut

## Create venv

### Update pip
`python -m pip install --upgrade pip`

### Install django
`python -m pip install Django`

### Part 1
`python -m django --version`

#### Create a project 
`django-admin startproject mysite`

#### Verify project
`cd mysite`
`python manage.py runserver`

#### Create the Polls app
`python manage.py startapp polls`

#### Add code to polls/views.py - to return an HttpResponse()
#### Edit mysite/urls.py - add this file to provide the route for polls

### Part 