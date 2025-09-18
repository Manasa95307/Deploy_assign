Run Locally:

git clone https://github.com/Manasa95307/Deploy_assign.git
cd student-api
npm install

Create .env file:

MONGO_URI= mongodb+srv://manasahv04_db_user:Manasa1629@clusterstudentapi.or2xni6.mongodb.net/studentAPI
PORT=3000

Start server:

npm start

API runs at http://localhost:5000

Deployed API

https://student-api-manasahv.onrender.com

Add Student

POST /api/students

{
  "name": "Alice",
  "age": 20,
  "course": "BTech",
  "year": "2nd"
}

Get All Students

GET /api/students
