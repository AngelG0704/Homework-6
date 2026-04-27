Project Description - 

This project was essentially a backend for a task manager API, this would be the part that processes information that a user would
enter if this was a fully made app with a frontend. I am able to to create tasks that contain a title, description, priority
and a completion status. I was able to then use actions that would create, read, update, and delete tasks. 

How to Run -

1. Prerequisites 

Java 17 or 21
Maven

2. Clone Repository 

git clone https://github.com/AngelG0704/Homework-5.git

cd campus-taskboard

3. Run the application

mvnw.cmd spring-boot:run

4. Confirm it's running

look for Started CampusTaskboardApplication in the console and then the server should be avalible at http://localhost:8080/api/tasks

API endpoints- 

Method            Endpoint         Description
GET               /api/tasks       Returns all tasks
GET               /api/tasks/{id}  Returns a single tasks by ID
POST              /api/tasks       Creates a new task
PUT              /api/tasks/{id}   Updates an existing task
DELETE          /api/tasks/{id}    Deletes a task

Video Submission-

https://youtu.be/quQYKC-TigY
