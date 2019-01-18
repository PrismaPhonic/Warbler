# Warbler
Warbler is a mock twitter clone built completely as a backend application. Users can signup/login, follow other users, be followed by other users, create warbles(similar to tweets), as well as direct message other users. User authentication/authorization is done with bcrypt for verification and sessions are used to store current user information. The backend is built in Flask and Jinja is used as a templating system for the HTML. PostgreSQL is used as the relational database and communicated with via SQLAlchemy. Tests are written for the views and models using the unittest module. Feel free to run the app locally or go to the live hosted heroku site: [warbler](https://warbler-pf.herokuapp.com/).

![warbler screenshot](screenshots/warbler-screenshot.png)

# Local Setup
## Creating a Virtual Environment

```terminal
$ python3 -m venv venv
```

This will create a virtual environment in the folder venv (do this inside the
project directory after you clone it)

## Using the virtual environment

Let's now use our virtual environment and then install the necessary python
modules

```terminal
$ source venv/bin/activate
$ pip3 install -r requirements.txt
```

Now let's run the project!

```terminal
$ flask run
```

You should be able to access warbler at `http://localhost:5000/`
