# ToDo-app

It's just the backend of the app.

### What's been used so far:

* Python 3.10.2
* Django 3.2.11
* Django Rest Framework 3.13.1
* Django cors headers 3.11.0

All tested and run on Windows 11 Pro x64.

### Installation:

* Get Python 3.10 whether from the Microsoft store or python.org

* Clone this project.

* Using the command line, go to the repository directory and install virtualenv using pip like this: `pip install virtualenv`

* Then, create a virtual environment using `virtualenv mysite` (use whatever name you find best).

* After it's ready, activate it using `<venv name>\Scripts\Activate` and install the requirements to run the backend with`pip install -r requirements.txt`.

* Move into the todolist directory and run `py manage.py runserver`.

* Access the api through http://localhost:8000/api/


__User and password for the admin site (http://localhost:8000/admin/) is admin/admin.__
