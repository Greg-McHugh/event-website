# COP4710
Database Systems Project 

1. install Django:
	https://docs.djangoproject.com/en/2.1/topics/install/
	For this project, I used MySQL

2. In event-website/RSOsystem/RSOsystem/settings.py, you will need to change:


		DATABASES = {
	    'default': {
	        'ENGINE': "django.db.backends.mysql",
	        'NAME': 'rso_system',					//make sure this database exists on your system 'create database rso_system;'
	        'USER': 'greg',						//change to a user on your system
	        'PASSWORD': 'password',					//change to the password of the above user
	        'HOST': '',
	        'PORT': '',        
	    }
	}

3. in event-website/RSOsystem/
		$python manage.py
