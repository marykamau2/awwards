### Project Name
 - Awwards

### Author
- Mary Kamau
### Description
- This is an application that allows users to post their projects and also can view other people's projects As a user of the web application you will be able to:

 - Register and sign up for the applications
 - A user can post his/her own project
 - A user can also rate and review other people projects basing on different factors
### Setup and installations
- Clone Project to your machine
- Activate a virtual environment on terminal: source virtual/bin/activate
- Install all the requirements found in requirements file.
- On your terminal run python3.8 manage.py runserver
- Access the live site using the local host provided
### Getting started

### Prerequisites
- python3.8
- virtual environment
- pip
## Clone the Repo and rename it to suit your needs.
- git clone https://github.com/marykamau2/awwards
- Initialize git and add the remote repository
- git init
- git remote add origin <your-repository-url>
### Create and activate the virtual environment
- python3.8 -m venv virtual
- source virtual/bin/activate
### Install dependancies
- Install dependancies that will create an environment for the app to run pip install -r requirements.txt

### Make and run migrations
- python3.8 manage.py check
- python manage.py makemigrations awwards
- python3.8 manage.py sqlmigrate awwards 0001
- python3.8 manage.py migrate
### Run the app
- python3.8 manage.py runserver
- Open localhost:8000

### Testing the Application
- python3.8 manager.py tests

### Built With
- Python3.6
- Django
- Boostrap
- HTML
- CSS
### Licence
- This project is under the MIT licence