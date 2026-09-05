# Flask_and_MongoDB_Assignment

This repository contains my submissions for the Flask and MongoDB DevOps assignment. 

## Files Included
* `task1_api.py`: A simple Flask API route that reads data from `data.json` and returns it as a JSON response.
* `data.json`: The backend data file used for Task 1.
* `task2_app.py`: A Flask application that connects to MongoDB Atlas. It takes form input, saves it to a database, and redirects on success. It also handles connection errors.
* `templates/index.html`: The frontend HTML form for Task 2.
* `Documentation.pdf`: Contains all required screenshots, commands, and explanations for the assignment.

## How to Run Task 1 (API Route)
1. Install Flask: `pip install flask`
2. Run the file: `python task1_api.py`
3. Open a browser and go to `http://127.0.0.1:5000/api`

## How to Run Task 2 (MongoDB Form)
1. Install Flask and PyMongo: `pip install flask pymongo`
2. Update the `MONGO_URI` variable in the script with a valid MongoDB Atlas connection string.
3. Run the file: `python task2_app.py`
4. Open a browser and go to `http://127.0.0.1:5001`
