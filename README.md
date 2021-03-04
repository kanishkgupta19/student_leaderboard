# This is an assignment for Full Stack Developer Internship (AlmaBetter) #
Stack         |  Technology
------------- | -------------
Frontend      | React Js
backend       | Django REST Framework
Database      | mySQL
Deployed on   | Heroku

### Local Start Application: ###
1. Setup Database:
	i. Import the .sql file in Databse folder to your local database.
2. Setup Backend
	i. Add MySQL database credentials to backend(django) application in settings.py
	ii. Install all the python packages from requirements.txt
	iii. Run `python manage.py runserver` to start the server
	iv. It will run on your localhost:8000
3. Setup Frontend
	i. run "npm start" in the frontend repository
	ii. It will start at localhost:3000

### LIVE SERVER: ###
1. Application Link=> https://studentleaderboard-kanishk.herokuapp.com/

2. API Link=> https://studentleaderboard-api.herokuapp.com/students-records/

#### APIs ####
i. ViewAll:'https://studentleaderboard-api.herokuapp.com/students-records/view-all/' ==> [GET]
ii. Create:'https://studentleaderboard-api.herokuapp.com/students-records/create/' ==> [POST]
iii. Update:'https://studentleaderboard-api.herokuapp.com/students-records/update/<str:Id>' ==> [POST]
iv. Delete:'https://studentleaderboard-api.herokuapp.com/students-records/delete/<str:Id>' ==> [POST] 
