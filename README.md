# Task Manager App!
------
Task Manager demonstrates my skills in Data Centric Development. This application performs create, read, update, and delete calls, otherwise known as CRUD calls, to a MongoDb database.
All built with a micro web framework called Flask. Users will be able to register, see their profile, log out, and log back in again. Registered users will be able to add a new task, 
which includes selecting a due date using Materialize's datepicker component, and toggle a swich to mark the task as urgent. Users will also be able to edit tasks, but will only be permitted 
to edit and or delete their own tasks, not any of the tasks submitted by others.


## Languages/Frameworks used
- HTML5
- CSS3
- Bootstrap
- Python3
- Flask

## Requirements
```
click==7.1.2
dnspython==2.0.0
Flask==1.1.2
Flask-PyMongo==2.3.0
itsdangerous==1.1.0
pymongo==3.11.2
Werkzeug==1.0.1
```

## Deployment
Github pages doesn't really like flask designed sites.. So I used Heroku!

Installing Flask
```
gitpod /workspace/thorin-and-co_flask-app $ pip3 install Flask
```
Starting Flask
```
gitpod /workspace/thorin-and-co_flask-app $ python3 run.py
```
Installing Heroku
```
gitpod /workspace/thorin-and-co_flask-app $ npm install -g heroku
```
Heroku Login
```
gitpod /workspace/thorin-and-co_flask-app $ heroku login -i
```
```
heroku: Enter your login credentials
Email: randyaajrsp@gmail.com
Password: *****************
Logged in as randyaajrsp@gmail.com
```

## User Stories
> Marcela Estay<br>
> *Very useful application. I find the user interface to be extremely (new) user friendly.*

> Ronda Lee<br>
> *Task Manager has helped me with keeping uptodate with my daily tasks. Very easy to get started with, much like Facebook and or Twitter.* 

> Micheal Opal<br>
> *This has been my go to for keeping track of my studies. Highly recommend!!* 


## WireFrames
Home Page <br>
![Home Page](static/img/1.png) <br>
Registration Page <br>
![alt text](static/img/2.png) <br>
Add Task Page <br>
![alt text](static/img/3.png) <br>
Manage Tasks Page <br>
![alt text](static/img/4.png) <br>

## Live Link (Heroku)
[Task Manager](https://task-manager-randy.herokuapp.com/get_tasks)