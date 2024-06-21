# SchoolApp
An app that can be used to maintain records of all the students enrolled in a school.
<br>
This is a FastAPI application for managing students.

Features
Create a new student
Get a list of students
Installation
Clone the repository:
git clone https://github.com/yourusername/yourrepository.git
Install the dependencies:
pip install -r requirements.txt
Create the cofig.ini.

[DATABASE]
DB_USERNAME = DB_USERNAME1
DB_PASSWORD = DB_PASSWORD1
Usage
Start the FastAPI server:
uvicorn main:app --reload
Open your browser and visit http://localhost:8000.
API Endpoints
POST /students/: Create a new student. The request body should be a JSON object with the student details.

GET /students/: Get a list of students. You can filter the students by country and age, and paginate the results.
