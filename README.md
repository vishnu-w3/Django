### Simple Employee Directory: A beginner-friendly Django project, ideal for those learning Django fundamentals.

1.) **pip freeze** - To see the packages that are installed on the computer.

2.) **pip install virtualenv** - To install the virtual environment explicitly.

3.) To activate env , **source env/Scripts/activate** -> is the path to activate.bat file and also activates the env.

4.) To deactivate env, execute **deactivate** cmd in gitbash.

5.) To install Django, cmd -> **pip install django**

6.) To create a project, **django-admin startproject mysite .** .This will create a mysite directory in your current directory. The dot . let django to create project (manage.py) in the root directory.

7.) To run the project -> **python manage.py runserver**

8.) To create a database tables, we need to run two commands -> **python manage.py makemigrations** and **python manage.py migrate**

9.) Django gives you some default database tables to manage the admin panel , run this **python manage.py migrate** command to get the database tables created.

10.) To get the login credentials to log in to the admin panel, we create a super user using the command line -> **python manage.py createsuperuser**
