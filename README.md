# Django-manage.py-anywhere
Run manage.py commands from any directory of your Django project.

# Installation is quick and simple
One line installer:   
```
pip install django_managepy_anywhere
```

# Usage
Run ```manage.py``` from any directory of your Django project. It will find closest manage.py file to your current position and execute it. 
The closer the file, the faster it will be found and executed. Usually, if you're within your Django code directory, manage.py will be found and executed very quickly.

# Version 2.0
While version 1.0 was based on bash, I completely rewrote the script in v2.0 and now it uses Python to execute. Should be more reliable in different environments, especially in
Docker.