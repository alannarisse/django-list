# Shopping list app API with Python and Django

A shopping list app API for Thinkful's PYTHON-DJANGO-001 learning module.

This app implements [this API spec](https://documenter.getpostman.com/view/2364768/listful-app-api/RW1aJfDp#b082c957-558e-42aa-9ea0-f0bc22c24538), and in so doing, can support [this client app](https://github.com/Thinkful-Ed/listful-app-client).

# Installation Instructions
1. Install python 3
    Check to see if you have python 3 on your machine. In a terminal, check for version >
    ```python --version``` or ```python3 --version```
    If you don’t have some version of Python 3.x, download Python 3.x from python.org.
2. Install virtualenv. check to see if it's installed on your machine:
    ```virtualenv --version```
    If it's not there, run > ```pip install virtualenv```
3. Create a virtual env. Go to the project's main directory (where the venv directory lives) and run >
    ```virtualenv venv```
    FYI, you could call your virtual env whatever you want, but 'venv' is a good standard name to call your virtual env. 
4. To activate it type >
    ```source venv/bin/activate```
    (venv) will show up in your terminal prompt to tell you that you are now inside your virtual env.
5. Install Django into your venv > 
    ```pip install django```
    Run > ``pip freeze`` to verify django is installed in your venv.

    To deactivate your virtualenv, run > ```deactivate venv```
    Or you can just close your terminal window.

6. Start up the server. cd into ShoppingList and run >
    ```python manage.py runserver```
    You can stop your python server by pressing Control + C