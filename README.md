# Open Source Help Community

![OSHC](https://avatars0.githubusercontent.com/u/23719480?v=3&s=200)

We are trying to create a medium where people who want to start with contributing to open sources and open source contributors meet and discuss their thoughts and questions([Getting Started With Open Source](https://github.com/tapasweni-pathak/Getting-Started-With-Contributing-to-Open-Sources)). 

Website [WIP]

[How it looks currently](https://gyazo.com/8395caa42290fb5a7d32d6b75c07ff53)

This is using [Django(1.7.6)](https://www.djangoproject.com/) and [Bootstrap](http://getbootstrap.com/).
Feel free to suggest a better design.

## To run this in your local

1. Clone this repository using
	```
	git clone git@github.com:OpenSourceHelpCommunity/OpenSourceHelpCommunity.github.io.git
	```

2. Go inside main Django app [Instructional video on installing Django](https://youtu.be/qgGIqRFvFFk)
	```
	cd oshc
	```

3. Syncdb

	```
	python manage.py syncdb
	```

4. Change path to static files in settings.py

	Right now this file is having path of my local. Just change the machine's username to your own.

	```
	STATICFILES_DIRS =  ()
	```
4. Run the app
	```
	python manage.py runserver
	```


Feel free to raise and fix issues.
For any questions, join #oshc-dev on Slack.

Note : All design related tasks have reward associated with them.

