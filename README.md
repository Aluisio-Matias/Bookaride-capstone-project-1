![BOOKARIDE](https://user-images.githubusercontent.com/91992866/182531145-2ba03f22-5c8e-4c3f-8595-c9d98ce0adaf.png)
___
BOOKARIDE is a transportation booking website that allows users to reserve online and admins (or the business owner) to keep track of all the reservations made by all users in the database. This is my Capstone Project One for Springboard's Software Engineering career track. Here's a link to the fully deployed project: [BOOKARIDE]

## Features

- Users (clients) can register to book online and keep track of all of their reservations. 
- Admin users can keep track of all of the reservations made by all users, and also create or edit reservations for any user (client) in the database. 
- Users receive a text message confirming their booking has been created successfully using the [Twilio API].   
- Allows users and admins to send booking email confirmations to any email using Python. 
- Auto search for an address using the [Mapquest API]
- User authentication with bcrypt.
- Password hashing with bcrypt for secure password storage.

>[BOOKARIDE] app's goal is to make it easier for users and admins
>to manage their bookings all in one place.
>This current version allows anyone to create an admin user to test the app's functionality.
>The real world app will not allow admin users to be created on the website. 
>Improvements and new features updates will be coming along the way! 

## Tech

BOOKARIDE uses multiple programming languages and a number of open source projects to work properly:

- HTML, CSS and JavaScript for front-end design
- [Twitter Bootstrap] - great UI boilerplate for a modern and responsive app.
- [Fontawesome] - Free icons
- [Python] and many of it's packages for backend development.
- [Jinja] to run code similar Python inside HTML
- [Flask] for many backend utilities
- [jQuery]
- [SQLAlchemy], the Python SQL toolkit and Object Relational Mapper.
- [PostgreSQL] database management system.

---

## Installation
Clone git repo:
```sh
gh repo clone Aluisio-Matias/capstone-project-1
```
On your command lind, cd into your directory and create a virtual enviroment:
```sh
$ python3 -m venv venv
```
Activate your venv:
```sh
your_directory$ source venv/bin/activate
```

Install requirements inside your venv on your first time running the app:
```sh
(venv) $pip install requirements.txt
```
Start the server with Flask
```sh
(venv)$ flask run
```
Go into your browser (preferably Google Chrome) and open the server on port:5000
```sh
http://localhost:5000/
```

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job.) 

[BOOKARIDE]:<https://book-a-ride-app.herokuapp.com/>
[Twilio API]: <https://www.twilio.com/>
[Mapquest API]: <https://developer.mapquest.com/>
[Python]: <https://www.python.org/>
[Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
[jQuery]: <http://jquery.com>
[Flask]: <https://flask.palletsprojects.com/en/2.2.x/>  
[Jinja]: <https://jinja.palletsprojects.com/en/3.0.x/>
[SQlalchemy]: <https://www.sqlalchemy.org/>
[PostgreSQL]:<https://www.postgresql.org/docs/>
[Fontawesome]: <https://fontawesome.com/>
