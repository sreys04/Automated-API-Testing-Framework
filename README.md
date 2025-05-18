# Automated-API-Testing-Framework
Project Objective:
To build a lightweight and scalable framework for testing RESTful APIs using Postman and automating the process through Python and CI/CD pipelines.

🚀 How It Works:
Postman collections define requests and assertions (status code, body, schema).

Newman runs the tests from CLI or via Python.

Python script wraps Newman execution and generates HTML reports.

GitHub Actions automates test execution on every push.

📋 Sample Tests Include:
GET /users

POST /login

PUT /profile/{id}

DELETE /user/{id}

Negative cases (401 Unauthorized, 404 Not Found)

🧪 CI/CD Integration:
GitHub Actions .yml script runs run_tests.py on every commit.

Failures trigger alerts via GitHub checks.
