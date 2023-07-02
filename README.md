# Python Commands (Linux based, can use git bash on Windows)

- Check python version: `python3 --version`
- Upgrade pip: `python3 -m pip install -U pip`
- Install virtualenv package: `python3 -m pip install virtualenv`
- Create virtual environment : `python3 -m virtualenv my_env`
- Activate venv: `source my_env/env/activate` or `source my_env/Scripts/activate` (for windows)
- Install django: `python3 -m pip install django`
- Create requirement.txt: `python3 -m pip freeze > requirements.txt`

# Django Commands

- Create new project: `django-admin startproject my_django_project` (Try running cmd as administrator if the command doesn't work?)
- Run server: `python3 manage.py runserver`
- List migrations: `python3 manage.py showmigrations`
- Create migratiosn: `python3 manage.py makemigrations`
- Migrate created migrations: `python3 manage.py migrate`
- Start new app: `python3 manage.py startapp my_app`

### User related

- Create super user: `python3 manage.py createsuperuser` (admin:admin)
- Change password: `python3 manage.py changepassword new_password`

# Git commands

- Initialise a readme: `echo "# my_django_project" >> README.md`
- Init a git project : `git init` (convert a project to git managed)
- add files: `git add .`
- create a commit: `git commit -m "first commit"`
- ` git branch -M main`
- adding origin: `git remote add origin https://github.com/asutkarpeeyush/my_django_project.git`
- pushing the code: `git push -u origin main`