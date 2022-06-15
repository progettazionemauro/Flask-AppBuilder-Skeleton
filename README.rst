Base Skeleton to start your application using Flask-AppBuilder

Prima versione di FAB con trasferimento da: REPLIT --> GITHUB --> LOCALE
--------------------------------------------------------------clear


Seconda versione di FAB con trasferimento da: LOCALE --> GITHUB --> REPLIT
--------------------------------------------------------------


- Install it::

	pip install flask-appbuilder
	git clone https://github.com/dpgaspar/Flask-AppBuilder-Skeleton.git

- Run it::cd 
    $ export FLASK_APP=app
    # Create an admin user
    $ flask fab create-admin
    # Run dev server
    $ flask run


That's it!!

Vedere qui: https://flask-appbuilder.readthedocs.io/en/latest/breaking.html

Inizializzazione del nuovo progetto
. venv/bin/activate
(venv)$ flask fab create-app
Your new app name: first_app
Your engine type, SQLAlchemy or MongoEngine [SQLAlchemy]:
Downloaded the skeleton app, good coding!
(venv)$ cd first_app
(venv)$ export FLASK_APP=app
(venv)$ flask fab create-admin
Username [admin]:
User first name [admin]:
User last name [user]:
Email [admin@fab.org]:
Password:
Repeat for confirmation:
