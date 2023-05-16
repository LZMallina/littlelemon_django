# Meta Backend Certification Week 5 Graded Assignment

## Design and Build a simple Django app

### Step 1: create virtual environment

> py -3 -m venv .venv
>.venv\scripts\activate
* In VS Code, open the Command Palette (View > Command Palette or (Ctrl+Shift+P)). Then select the Python: Select Interpreter command:

* Run Terminal: Create New Terminal (Ctrl+Shift+`) from the Command Palette, which creates a terminal and automatically activates the virtual environment by running its activation script.

### Step 2: setup python and django

* update pip in the virtual environment

> python -m pip install --upgrade pip

* install Django in the virtual environment

>python -m pip install django

>python -m django --version

### Step 3: Create Django project

* startup project

>django-admin startproject web_project .

* Create an empty development database

>python manage.py migrate

### Step 4: Run development server to ensure setup is ready

> python manage.py runserver

### Step 5: Create a Django app

> python manage.py startapp app_name

### Step 6: Exit virtual environment

> deactivate

