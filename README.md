# COP4710
Database Systems Project 

1. install Django:
   https://docs.djangoproject.com/en/2.1/topics/install/
   $sudo pip install django

2. For this project, I used MySQL. Make sure mysql and the necessary module are installed.
   $sudo apt-get install mysql-server python-mysqldb

2. In event-website/RSOsystem/RSOsystem/settings.py, you will need to change:


		DATABASES = {
	    'default': {
	        'ENGINE': "django.db.backends.mysql",
	        'NAME': 'rso_system',				// this database must exist on your system 'create database rso_system;'
	        'USER': 'greg',					// change to a user on your system
	        'PASSWORD': 'password',				// change to the password of the above user
	        'HOST': 'localhost',
	        'PORT': '',        
	    }
	}

3. in the directory event-website/RSOsystem/
   enter at terminal $python manage.py runserver 8080

4. visit localhost:8080 in your web browser to test the website
