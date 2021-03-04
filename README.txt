This is an assignment for Full Stack Developer Internship

Frontend -> react Js
backend -> Django REST Framework
Database -> mySQL
Deployed on-> Heroku

Local Start Application:
-> Setup Database:
	 A Import the .sql file in Databse folder to your local database.
-> Setup Backend
	 1. Add MySQL database credentials to backend(django) application in settings.py
	 2. Install all the python packages from requirements.txt
	 3. Run "python manage.py runserver" to start the server
	 4. It will run on your localhost:8000
-> Setup Frontend
	1. run "npm start" in the frontend repository
	2. It will start at localhost:3000

LIVE SERVER:
Application Link=> https://studentleaderboard-kanishk.herokuapp.com/

API Link=> https://studentleaderboard-api.herokuapp.com/students-records/

APIs
'ViewAll':'https://studentleaderboard-api.herokuapp.com/students-records/view-all/' ==> [GET]
'Create':'https://studentleaderboard-api.herokuapp.com/students-records/create/' ==> [POST]
'Update':'https://studentleaderboard-api.herokuapp.com/students-records/update/<str:Id>' ==> [POST]
'Delete':'https://studentleaderboard-api.herokuapp.com/students-records/delete/<str:Id>' ==> [POST] 