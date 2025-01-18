# Simple Task Tracker

Simple Task Tracker is a simple web application to manage tasks. You can add, complete, and delete tasks easily from your browser.
All data is saved in an SQLite database.

## Features
1. **List Tasks**: Displays all tasks with their status.
2. **Add Tasks**: Allows users to add new tasks via a simple form.
3. **Mark Tasks as Completed**: Updates the status of a task to "Completed."
4. **Delete Tasks**: Removes a task from the list.

## How to Run
2. **Check the Docker**: Ensure you have Docker installed on your machine and it is running. If not, download and install it from Docker's official website.
2. **Clone the Project**: git clone <>, cd SimpleTaskTracker
3. **Run the app with Docker**: docker-compose up --build
4. **Open your browser and go to**: http://localhost:5000

## Technologies Used
- Flask (Backend)
- SQLite (Database)
- HTML & CSS (Frontend)
- Docker (To run the app)

## File Overview
**app.py**: Main application code.
**templates/index.html**: Web page design.
**Dockerfile**: Docker setup.
**docker-compose.yml**: Runs everything in a container.
**requirements.txt**: List of Python libraries needed.

## Notes
-All tasks are saved in an SQLite database file (tasks.db).
-No setup needed for the database—it works out of the box.


**Bugrahan ARIK  39288**