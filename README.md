# CRUD Application with Python-Flask and React as frontend
 

### Deliverables

Deploy the application in CodeSpaces.

1. Login to GitHub Account
2. Fork the repository (You can clone and upload too)
3. In the repository, create a new Codespaces Environment
4. Run the application



## Structure of the application

1. backend (app.py)
2. database (mydatabase.db)
3. frontend (_frontend/users)

## Backend - You need a terminal to run the application
The back end of the application is based on Flask library. The steps to run the application are as follows:

1. Initiate the virtual environment 
```python3 -m venv env```
2. Activate the env
in Windows run ```env\source\activate.bat```
in  Mac OS: ```source env/bin/activate```
3. install the needed libraries
```pip install flask flask_cors```
4. run the application
```python app.py``` (note that python should be installed on your machine, or you can run it on a virtual environment/GitHub Codespaces)

## Database

The database is based on SQLite. If the database does not exist, it will be created automatically.


## Frontend -You need a new terminal to run the application

The frontend is based on React library. The steps to run the application are as follows:
 
 1. ```cd _frontend/users/```
 2. npm i
 3. npm run dev
