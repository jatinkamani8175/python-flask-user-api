🧠 User Management REST API using Flask
✅ Objective
A simple REST API built with Flask for managing user data using in-memory storage (Python dictionary). Tested using Postman.

🔧 Tech Stack
Python

Flask

Postman (for testing)

📌 Features
GET / → API health check

GET /users → Get all users

GET /users/<user_id> → Get user by ID

POST /users → Add a new user

PUT /users/<user_id> → Update user by ID

DELETE /users/<user_id> → Delete user by ID

🔄 Sample JSON Body for POST/PUT
json
Copy
Edit
{
  "id": "1",
  "name": "Kamani Jatin",
  "email": "jatin1802@gmail.com"
}
📸 Testing
All endpoints were tested using Postman with the following headers:

pgsql
Copy
Edit
Content-Type: application/json
📁 How to Run
Install Flask:

bash
Copy
Edit
pip install flask
Run the application:

bash
Copy
Edit
python app1.py
The API will be available at http://127.0.0.1:5000/
