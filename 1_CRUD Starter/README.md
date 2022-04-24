# CRUD using GraphQL and Django

Installation Instruction

Make a virtual environment in a seperate directory

```
(terminal_path/mydir) python -m venv env
```

Copy this directory where virtual environment was installed, then activate the environment

```
(terminal_path/mydir) env\Sripts\activate
(env)(terminal_path/mydir)
```

Now install the requirement.txt file

```
(env)(terminal_path/mydir) pip install -r requirements.txt
```

Make migrations for the SQLITE database

```
(env)(terminal_path/mydir) python manage.py migrate
```

After migrations create the superuser

```
(env)(terminal_path/mydir) python manage.py createsuperuser
```

Now start the server

```
(env)(terminal_path/mydir) python manage.py runserver
```
