# Note Taking CRUD App
This note taking program was written using Python, Tkinter for the UI, and SQL queries to communicate with the MySQL database. I created this app to practice writing CRUD applications using a SQL database.

# DEMO 

![grab-landing-page](https://github.com/SamuelAlmanza/note_taking_app/blob/master/NotesCRUD.gif)

To start the app:
1. Install from requirements.txt 
2. Run your mysql server 
3. Update your server information in the source code:

conn = mysql.connector.connect(
  host="localhost",
  port=3306,
  user="root",
  passwd=""
)


CREDIT:

Project based on Effiong Charles' Note Taking App Tutorial 

https://levelup.gitconnected.com/build-a-note-taking-app-with-mysql-backend-in-python-927b4c5fad91
